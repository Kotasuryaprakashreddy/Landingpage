# Landingpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pollution Free Environment</title>
    <link rel="stylesheet" href="landingpage.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <h1>Pollution Free Environment</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="https://www.freepik.com/search?format=search&last_filter=query&last_value=pollution+free+environment&query=pollution+free+environment">Home</a></li>
                    <li><a href="section1">About</a></li>
                    <li><a href="#">Blogs</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
            </nav>
        </header>
        <div class="hero">
            <h1>Pollution Free Environment</h1>
            
            <img src="https://img.freepik.com/free-vector/polluted-earth-icon_1308-27704.jpg?t=st=17
            32169983~exp=1732173583~hmac=4ddab2fd182d24d327faadcd8cd2e6b730e3498e9f2e97dc62efee780
            38afe1a&w=740" alt="Nature Image">
            <button onclick="display('section1')">Read More</button>
        </div>
        <div class="content">
            <div>
                <h2>Our Environment</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
            <div>
                <h2>Our Study</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            </div>
        </div>
        <footer>
            <p>&copy; save the earth</p>
        </footer>
        
    </div>
    <div id="section1">
        <h1>pollution free environment</h1>
        <p></p>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #4CAF50;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 0;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

.hero {
    text-align: center;
    padding: 50px 0;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 20px;
}

.hero button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: #fff;
    border: none;
    cursor: pointer;
    font-size: 1em;
}

.hero img {
    width: 100%;
    max-width: 600px;
    margin-top: 20px;
}

.content {
    display: flex;
    justify-content: space-between;
    padding: 50px 0;
}

.content div {
    width: 45%;
}

.content h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.content p {
    font-size: 1em;
    line-height: 1.6;
}

footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}
