<script>
	import '../routes/styles.css';
    import FaSearch from 'svelte-icons/fa/FaSearch.svelte';
</script>

<div class="navbar">
    <!-- search icon -->
    <div class="search-icon"><FaSearch/></div>
    <input type="text" placeholder="Search.."/>
    <!-- upload button -->
    <!-- login button -->
</div>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
    .navbar{
        width: calc(100vw); height:5.6rem;
        background-color: #1a1717;
        position: sticky; top:0; left:0;
        display: flex; justify-content: center; align-items: center;
    }
    .search-icon {
        height: 2.5rem;
        margin-right: 2rem;
        aspect-ratio: 1;
        color: white;

    }
    /* Style the search box inside the navigation bar */
    .navbar input[type=text] {
        width: calc(20vw);
        font-size: 17px;
    }
</style>

