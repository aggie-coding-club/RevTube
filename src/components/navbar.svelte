    <script>
        import '../routes/styles.css';
        import FaSearch from 'svelte-icons/fa/FaSearch.svelte';
    </script>

    <div class="navbar">

        <div class="search-container">
            <!-- search icon -->
            <div class="search-icon"><FaSearch/></div>
            <input type="text" placeholder="Search...">
        </div>
        <!-- upload button -->
        <!-- login button -->
        <button class="navbar-login">Log In</button>
    </div>


    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
        .navbar{
            width: calc(100vw); height:5.6rem;
            background-color: #1a1717;
            position: sticky; top:0; left:0;
            display: flex; justify-content: center; align-items: center;
        }
        .search-container {
            display: flex; justify-content: center; align-items: center;
            border-radius: 0.6rem;
            border: solid black 0.2rem;
            background-color: #605858;
            height: 3.5rem;
        }
        .search-icon {
            height: 2.25rem;
            margin-right: 1rem; margin-left: 1rem;
            aspect-ratio: 1;
            color: white;
            cursor: pointer;

        }
        /* Style the search box inside the navigation bar */
        .navbar input[type=text] {
            width: 20vw;
            height: 3rem;
            font-size: 16px;
            caret-color: white;
            color: white;
            background-color: transparent;
            outline: none;
            border: 0;
        }

        .navbar-login {
            height: 35px;
            width: 70px;
            border: 2px solid #fff;
            background-color: #1a1717;
            color: #fff;
            border-radius: 5%;
            font-size: 15px;
            font-weight: 600;
        }

        .navbar-login:hover {
            opacity: 0.8;
            background-color: #594e4e;
        }
    </style>

