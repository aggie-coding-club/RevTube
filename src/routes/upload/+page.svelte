<script>
	import { initializeApp } from 'firebase/app';
	import { getAuth, onAuthStateChanged, getRedirectResult } from 'firebase/auth';
	import { getStorage, ref, uploadBytes } from 'firebase/storage';

	const firebaseConfig = {
		apiKey: 'AIzaSyAMqkjErFLeHX3ETry6aVyktfaD8mduf5k',
		authDomain: 'acc-project-revtube.firebaseapp.com',
		projectId: 'acc-project-revtube',
		storageBucket: 'acc-project-revtube.appspot.com',
		messagingSenderId: '611649798395',
		appId: '1:611649798395:web:67656b7eb0696454caf05e',
		measurementId: 'G-BGW19TQT9Y'
	};

	// Initialize Firebase
	const app = initializeApp(firebaseConfig);
	const storage = getStorage();
	const storageRef = ref(storage, 'videos');

	let files;
	let video_url;
	$: if (files) {
		console.log(video_url);
		uploadBytes(storageRef, files[0]).then((snapshot) => {
			console.log('Uploaded blob!');
		});
	}
</script>

<div>
	<input type="file" bind:files />
	<h1>ghi</h1>

	<video>
		<source src={video_url} type="video/mp4" />
		<track kind="captions" />
	</video>
</div>
