<script>
	import '../routes/styles.css';
	import MdDehaze from 'svelte-icons/md/MdDehaze.svelte';
	import IoMdHome from 'svelte-icons/io/IoMdHome.svelte';
	import IoMdFolder from 'svelte-icons/io/IoMdFolder.svelte';
	import IoMdBook from 'svelte-icons/io/IoMdBook.svelte';
	import MdAccessTime from 'svelte-icons/md/MdAccessTime.svelte';
	import MdHistory from 'svelte-icons/md/MdHistory.svelte';
	import IoMdThumbsUp from 'svelte-icons/io/IoMdThumbsUp.svelte'
</script>

<div class="sidebar">	

	<div class="side-nav">
		<div class="icon-container"><div class="icon"><MdDehaze/></div></div>
	</div>

	<div class="sidebar-container">

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><IoMdHome /></div>
			</div>
			<span>Home</span>
		</a>

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><IoMdBook /></div>
			</div>
			<span>Subscriptions</span>
		</a>

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><IoMdFolder /></div>
			</div>
			<span>Library</span>
		</a>

		<div class="divider"></div>

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><MdHistory /></div>
			</div>
			<span>History</span>
		</a>

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><IoMdThumbsUp/></div>
			</div>
			<span>Liked Videos</span>
		</a>

		<a href="/" class="sidebar-btn">
			<div class="icon-container">
				<div class="icon"><MdAccessTime /></div>
			</div>
			<span>Watch Later</span>
		</a>

	</div>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
	.sidebar {
		display: flex;flex-direction: column; align-items: center;
		min-height: 100vh; width: 24rem;
		background-color: #1a1717; 
		font-family: "Roboto"; color: white;
	}
	.sidebar-container {
		width: 21.6rem; height: inherit;
		display: flex; flex-direction: column; align-items: center;
	}
	.side-nav {
		width: 20rem; display: flex; justify-content: flex-start; align-items: center;
		margin: 1rem 0 1.5rem 0;
	}
	.side-nav .icon-container {
		cursor: pointer;
	}
	.side-nav .icon-container:hover {
		background-color: #443f3f; border-radius: 50%;
	}
	.sidebar-btn {
		display: flex; color: white;
		width: 20rem; height: 4rem;
		align-items: center; text-decoration: none; border-radius: 1rem;
		font-size: 1.4rem; font-weight: 400;
		cursor: pointer;
	}
	.sidebar-btn:hover {
		background-color: #443f3f;
	}
	.sidebar-btn span {
		margin-left: 2rem;
	}
	.icon-container {
		width: 4rem; height: 4rem;
		display: flex; justify-content: center; align-items: center;
		color: white;
	}
	.icon {
		width: 2.4rem; height: 2.4rem;
	}
	.divider {
		width: 19.5rem; height: 0.2rem;
		background-color: rgb(112, 104, 104);
		margin: 1rem 0 1rem 0; border-radius: 2rem;
	}

</style>
