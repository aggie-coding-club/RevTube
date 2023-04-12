<script>
	import './styles.css';
	import Sidebar from '../components/sidebar.svelte';
	import Footer from "../components/footer.svelte"
</script>

<div class="app">
	<main>
		<div>
			<slot />
			<Sidebar />
			<Footer/>
		</div>
	</main>
</div>

<style>
	.app {
		margin: 0; border: 0; padding: 0;
	}
</style>
