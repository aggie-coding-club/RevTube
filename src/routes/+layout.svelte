<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
	import Navbar from '../components/navbar.svelte';
</script>

<div class="app">
	<main class="app-container">
		<Sidebar />
		<slot/>
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
	}
</style>
