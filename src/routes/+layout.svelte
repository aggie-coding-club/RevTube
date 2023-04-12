<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
</script>

<div class="app">
	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>

<style>
	.app {
		margin: 0; border: 0; padding: 0;
	}
</style>
