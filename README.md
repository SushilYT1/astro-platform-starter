<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sushil YT 1 Official</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Layout */
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            width: 100%;
            padding: 20px;
            background-color: #333;
            color: #fff;
            text-align: center;
            font-size: 24px;
        }

        /* Navigation */
        nav {
            margin: 20px;
            display: flex;
            gap: 15px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #ddd;
        }

        /* Page Sections */
        .page {
            display: none; /* Hide all pages by default */
            max-width: 800px;
            width: 90%;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        /* Show the active page */
        .active {
            display: block;
        }

        /* Footer */
        footer {
            margin-top: auto;
            padding: 10px;
            background-color: #333;
            color: #fff;
            width: 100%;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    Sushil YT 1 Official
</header>

<nav>
    <a href="#" onclick="showPage('home')">Home</a>
    <a href="#" onclick="showPage('about')">About</a>
    <a href="#" onclick="showPage('services')">Services</a>
    <a href="#" onclick="showPage('gallery')">Gallery</a>
    <a href="#" onclick="showPage('contact')">Contact</a>
</nav>

<!-- Page Sections -->
<div id="home" class="page active">
    <h2>Home</h2>
    <p>Welcome to our website! This is the home page where you can find an introduction to our content.</p>
</div>

<div id="about" class="page">
    <h2>About</h2>
    <p>Learn more about us on this page. We are dedicated to providing the best service to our clients.</p>
</div>

<div id="services" class="page">
    <h2>Services</h2>
    <p>We offer a variety of services to meet your needs. Contact us to learn more about what we offer.</p>
</div>

<div id="gallery" class="page">
    <h2>Gallery</h2>
    <p>Check out some photos of our work and team. We’re proud of what we’ve accomplished.</p>
</div>

<div id="contact" class="page">
    <h2>Contact</h2>
    <p>Get in touch with us. We’re here to help answer any questions you may have

Email :- sushillamichhane283@gmail.com</p>
</div>

<footer>
    &copy; 2024 . All rights reserved.
</footer>

<script>
    // Function to show the selected page and hide others
    function showPage(pageId) {
        // Hide all pages
        const pages = document.querySelectorAll('.page');
        pages.forEach(page => page.classList.remove('active'));

        // Show the selected page
        document.getElementById(pageId).classList.add('active');
    }
</script>

</body>
</html>