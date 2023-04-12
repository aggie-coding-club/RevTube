<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
</script>

<div class="app">
	<Sidebar/>
	<slot />
</div>

<style>
	.app {
		margin: 0; border: 0; padding: 0;
	}
</style>
