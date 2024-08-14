## HTML (index.html)
html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar">
        <ul class="nav-list">
            <li class="nav-item"><a href="#home">Home</a></li>
            <li class="nav-item"><a href="#about">About</a></li>
            <li class="nav-item"><a href="#services">Services</a></li>
            <li class="nav-item"><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home">
        <h1>Welcome to Our Website</h1>
    </section>
    <section id="about">
        <h1>About Us</h1>
    </section>
    <section id="services">
        <h1>Our Services</h1>
    </section>
    <section id="contact">
        <h1>Contact Us</h1>
    </section>

    <script src="scripts.js"></script>
</body>
</html>


### CSS (styles.css)
css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.navbar {
    position: fixed;
    width: 100%;
    background-color: #333;
    top: 0;
    z-index: 1000;
}

.nav-list {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

.nav-item {
    float: left;
}

.nav-item a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

.nav-item a:hover {
    background-color: #111;
}

section {
    padding: 60px;
    margin-top: 50px;
}

#home {
    background-color: #f4f4f4;
    height: 100vh;
}

#about {
    background-color: #ddd;
    height: 100vh;
}

#services {
    background-color: #ccc;
    height: 100vh;
}

#contact {
    background-color: #bbb;
    height: 100vh;
}


### JavaScript (scripts.js)
javascript
window.onscroll = function() {
    var navbar = document.querySelector('.navbar');
    if (window.pageYOffset > 50) {
        navbar.style.backgroundColor = "#222";
    } else {
        navbar.style.backgroundColor = "#333";
    }
};


    
  
