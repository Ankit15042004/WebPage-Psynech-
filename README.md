<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game List</title>
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 20px;
        background-color: #201b1b;
    }

    .navbar {
        background-color: #9b8c8c2d;
        overflow: hidden;
        display: flex;
        align-items: center;
        padding: 0 16px;
        border-radius: 10px;
    }

    .navbar a {
        display: block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
    }

    .navbar a:hover {
        background-color: #ddd;
        color: black;
    }

    .navbar .logo {
        font-size: 1.5em;
        font-weight: bold;
        margin-right: auto;
        display: flex;
        align-items: center;
    }

    .navbar .logo img {
        width: 30px;  /* Decreased size */
        height: 30px; /* Decreased size */
        margin-right: 10px;
        /* filter: blur(2px); */
        border-radius: 5px;
    }

    .search-container {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: auto;
        margin-bottom: auto;
    }

    .search-input {
        width: 200px;
        height: auto;
        padding: 7px;
        border: 1px solid #ccc;
        border-radius: 15px 0px 0px 15px;
        outline: none;
        font-size: 16px;
    }

    .search-button {
        padding: 6px;
        border: 1px solid rgb(255, 255, 255);
        background-color: rgb(19, 145, 19);
        border-radius: 0px 15px 15px 0px;
        cursor: pointer;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .search-button img {
        width: 20px;
        height: 20px;
        filter: invert(100%);
    }

    footer {
        position: absolute;
        width: 100%;
        bottom: 0;
        height: 60px;
        color: white;
    }
</style>
</head>
<body>
     <section><!-- Navbar Section Starts -->
    <div class="navbar">
        <a class="logo" href="#">
            <img src="images/Logo2.png" alt="Logo">
            PSYNECH
        </a>
        <div class="search-container">
            <input type="text" placeholder="Search..." class="search-input">
            <button class="search-button">
                <img src="https://img.icons8.com/ios-glyphs/30/000000/search.png" alt="Search">
            </button>
        </div>
        <a href="#home">HOME</a>
        <a href="#categories">CATEGORIES</a>
        <a href="#community">COMMUNITY</a>
        <a href="#events">EVENTS</a>

    </div>
    </section><!-- Navbar Section Ends -->

        <footer>
            <p>Copyrighted By Psynech Gaming & Technology PVT. LTD.</p>
        </footer>
</body>
</html>
