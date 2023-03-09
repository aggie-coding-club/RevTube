<script>
	import '../routes/styles.css';
    import { SvelteComponentTyped } from 'svelte';
    import { Box, Button } from 'chakra-ui-svelte';
	import ChevronCircleUp from 'svelte-icons/fa/FaChevronCircleUp.svelte';
</script>

<div class="sidebar">
	<ChevronCircleUp></ChevronCircleUp>
	<div class="sidebar-container">
	</div>
</div>

<style>
	.sidebar {
		display: flex;
		flex-direction: column;
		height: 100vh; width: 90vw;
		background-color: black;
	}
</style>
