# Lvl2digitecwebsite
Nicholas Kirton
This is my website for L2digitec 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pinoy Accounting Limited</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header>
        <h1>Pinoy Accounting Limited</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
    <div class="content">
        <section class="bg-image">
            <div class="overlay">
                <h2>Home</h2>
                <p>Welcome to Pinoy Accounting Limited</p>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Pinoy Accounting Limited. All rights reserved.</p>
    </footer>
</body>
</html>







#CSS

body, html {
    height: 100%;
    margin: 0;
    font-family: Calibri, Arial, sans-serif; /* Changed to Calibri */
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
    background: #444;
    text-align: center;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: white;
    padding: 10px 20px;
    display: inline-block;
}

nav ul li a:hover {
    background: #555;
}

.content {
    padding: 0; /* Remove padding to make the image fully fit */
}

.bg-image {
    background-image: url('images/Tax-Payments-Image-rawpixel-1024x683.jpg');
    height: 100vh; /* Full viewport height */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}

.overlay {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.5); /* Optional: Add a semi-transparent background to improve text readability */
    padding: 20px;
    border-radius: 10px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: relative; /* Change to relative to prevent overlap with content */
    width: 100%;
    bottom: 0;
}
