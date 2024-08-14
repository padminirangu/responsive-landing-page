# responsive-landing-page
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


