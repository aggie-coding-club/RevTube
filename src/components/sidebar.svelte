<script>
	import '../routes/styles.css';
    import { SvelteComponentTyped } from 'svelte';
	import FaAndroid from 'svelte-icons/fa/FaAndroid.svelte';
</script>

<div class="sidebar">
	<div class="icon">
		<FaAndroid></FaAndroid>
	</div>
	<div class="sidebar-btn-container">
	</div>
</div>

<style>
	.sidebar {
		display: flex;
		flex-direction: column;
		min-height: 100vh; width: 10rem;
	}
	.icon {
		font-size: 10rem;
		color: black;
	}
</style>
