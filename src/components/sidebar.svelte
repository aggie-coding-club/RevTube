<script>
	import '../routes/styles.css';
    import { SvelteComponentTyped } from 'svelte';
    import { Box, Button } from 'chakra-ui-svelte';
	import ChevronCircleUp from 'svelte-icons/fa/FaChevronCircleUp.svelte';
	import FaBars from 'svelte-icons/fa/FaBars.svelte';
</script>

<div class="sidebar">
	<div class="sidebar-container">
		<a href="/" class="sidebar-button">
			<div class="icon">
				<FaBars />
			</div>
			<span>Home</span>
		</a>
		<a href="/" class="sidebar-button">
			<div class="icon">
				<FaBars />
			</div>
			<span>Subscriptions</span>
		</a>
		<a href="/" class="sidebar-button">
			<div class="icon">
				<FaBars />
			</div>
			<span>Videos</span>
		</a>
	</div>
</div>

<style>
	.sidebar {
		display: flex;
		flex-direction: column;
		align-content: center;
		min-height: 100vh; 
		width: 12.5rem;
		padding: 10px 2vw;
		background-color: #1a1717;
	}

	.sidebar-button {
		display: flex;
		width: 100%;
		color: #fff;
		height: 40px;
		align-items: center;
		text-decoration: none;
		border-radius: 10px;
		font-size: 20px;
	}

	.sidebar-button:hover {
		background-color: #443f3f;
	}

	.icon {
		width: 10%;
		margin-right: 20px;
		margin-left: 5px;
		margin-top: 5px;
	}
</style>
