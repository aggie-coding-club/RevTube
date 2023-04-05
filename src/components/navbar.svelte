<script>
	import '../routes/styles.css';
</script>

<div class="navbar">
    <input type="text" placeholder="Search..">
</div>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
    .navbar{
        width: calc(100vw); height:5.6rem;
        background-color: #1a1717;
        position: sticky; top:0; left:0;
    }
    /* Style the search box inside the navigation bar */
    .navbar input[type=text] {
    float: right;
    padding: 6px;
    border: none; 
    margin-top: 12px;
    margin-right: calc(40vw);
    width: calc(20vw);
    font-size: 17px;
    }
</style>

