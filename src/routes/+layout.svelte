<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
	import Videoicons from '../components/videoicons.svelte';
</script>

<div class="app">
	<main>
		<slot />
		<Sidebar />
		<Videoicons />
	</main>
</div>

<style>
	.app {
		margin: 0; border: 0; padding: 0;
	}
	main {
		width: 100vw; height: 100vh;
		display: flex;
	}
</style> 
