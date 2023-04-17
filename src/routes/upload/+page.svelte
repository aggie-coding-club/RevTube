<script>
	import { initializeApp } from 'firebase/app';
	import { getAuth, onAuthStateChanged, getRedirectResult } from 'firebase/auth';
	import { getStorage, ref, uploadBytes } from 'firebase/storage';

	const firebaseConfig = {
		apiKey: 'AIzaSyAMqkjErFLeHX3ETry6aVyktfaD8mduf5k',
		authDomain: 'acc-project-revtube.firebaseapp.com',
		// databaseURL: 'YOUR_DATABASE_URL',
		projectId: 'acc-project-revtube',
		storageBucket: 'acc-project-revtube.appspot.com',
		messagingSenderId: '611649798395',
		appId: '1:611649798395:web:67656b7eb0696454caf05e',
		measurementId: 'G-BGW19TQT9Y'
	};

	const app = initializeApp(firebaseConfig);
	const storage = getStorage(app);
	const storageRef = ref(storage, 'videos');

	let files;
	let videoUrl;
	let uploadProgress = null;
	let uploadError = null;
	let uploadSuccess = null;

	const handleFileInput = (event) => {
		files = event.target.files;
		videoUrl = URL.createObjectURL(files[0]);
	};

	const handleUpload = () => {
		if (files) {
			uploadProgress = 0;
			uploadError = null;
			uploadSuccess = null;

			const uploadTask = uploadBytes(storageRef, files[0]);

			uploadTask.on(
				'state_changed',
				(snapshot) => {
					uploadProgress = (snapshot.bytesTransferred / snapshot.totalBytes) * 100;
				},
				(error) => {
					uploadError = error.message;
				},
				() => {
					uploadTask.snapshot.ref.getDownloadURL().then((downloadURL) => {
						videoUrl = downloadURL;
						uploadSuccess = 'Upload complete!';
					});
				}
			);
		}
	};
</script>

<div class="container">
	<h1 class="upL">Upload videos</h1>
	<input type="file" on:change={handleFileInput} />
	{#if videoUrl}
		<div class="video-container">
			<video controls>
				<source src={videoUrl} type="video/mp4" />
				Your browser does not support the video tag.
			</video>
		</div>
	{/if}
	{#if uploadProgress !== null}
		<p>Upload progress: {uploadProgress.toFixed(2)}%</p>
	{/if}
	{#if uploadError !== null}
		<p style="color: red;">Upload error: {uploadError}</p>
	{/if}
	{#if uploadSuccess !== null}
		<p style="color: green;">{uploadSuccess}</p>
	{/if}
	<button class="upload-btn" on:click={handleUpload}>Upload</button>
</div>

<style>
	.upL {
		text-align: center;
		font-size: 3rem;
		color: rgb(246, 246, 246);
	}

	.container {
		background-color: rgb(18, 20, 21);
	}

	.video-container {
		margin-top: 20px;
	}

	.video-container video {
		width: 100%;
		height: 100%;
	}

	.upload-btn {
		margin-top: 20px;
		padding: 10px 20px;
		border: none;
		background-color: #4caf50;
		color: white;
		cursor: pointer;
	}

	.upload-btn:hover {
		background-color: #3e8e41;
	}
</style>
