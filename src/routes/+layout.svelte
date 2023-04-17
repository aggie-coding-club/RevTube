<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
	import Navbar from '../components/navbar.svelte';
	import Videoicons from "../components/videoicons.svelte";
	let content_width="calc(100vw - 24rem)";
</script>

<div class="app">
	<main class="app-container">
		<Navbar/>
		<Sidebar bind:show={content_width}/>
		<div class="content" style="width: {content_width};">
			<Videoicons/>
			<slot />
		</div>
	</main>
</div>

<style>
	.app {
		margin: 0;
		border: 0;
		padding: 0;
	}

	.app-container{
		display: flex;
		position: relative;
	}
	.content {
		position: absolute;
		top: 5.6rem;
		right: 0;
	}
</style>