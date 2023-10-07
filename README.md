//Html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mussoorie International School</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Welcome to Mussoorie International School</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#courses">Courses</a></li>
                <li><a href="#admissions">Admissions</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla eget mauris nec mi ullamcorper feugiat.</p>
    </section>

    <section id="courses">
        <h2>Our Courses</h2>
        <ul>
            <li>Course 1</li>
            <li>Course 2</li>
            <li>Course 3</li>
        </ul>
    </section>

    <section id="admissions">
        <h2>Admissions</h2>
        <p>Interested in joining our school? Learn more about our admission process <a href="admissions.html">here</a>.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <address>
            <p>Mussoorie International School</p>
            <p>123 School Street</p>
            <p>Dehradun, India</p>
            <p>Email: info@mischool.edu</p>
            <p>Phone: +1 234-567-8901</p>
        </address>
    </section>

    <footer>
        <p>&copy; 2023 Mussoorie International School</p>
    </footer>
</body>
</html>


// css


body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}


body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
}


header {
    background-color: #007bff; 
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}


nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li:last-child {
    margin-right: 0;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

section {
    background-color: #fff;
    padding: 2rem;
    margin: 2rem 0;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}


h1, h2 {
    color: #333;
}


footer {
    background-color: #007bff;
    color: #fff;
    text-align: center;
    padding: 0.5rem 0;
}


a {
    color: #007bff; 
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
