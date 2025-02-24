@media screen and (max-width: 768px) {
    nav ul {
        text-align: center;
        padding: 0;
    }

    nav ul li {
        display: block;
        margin: 10px 0;
    }

    .home {
        padding: 20px;
    }

    .btn {
        width: 100%;
        display: block;
        text-align: center;
    }
}

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f4f4f4;
    color: #333;
}

/* Header & Navigation */
header {
    background: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #f4a261;
}

/* Home Section */
.home {
    text-align: center;
    padding: 50px;
}

.btn {
    display: inline-block;
    padding: 10px 20px;
    color: white;
    background: #f4a261;
    text-decoration: none;
    border-radius: 5px;
}

.btn:hover {
    background: #e76f51;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
}

<section class="skills">
    <h2>Skills & Resume</h2>
    <ul>
        <li>HTML, CSS, JavaScript</li>
        <li>React, Bootstrap</li>
        <li>Python, Django</li>
    </ul>
</section>

<section class="contact">
    <h2>Contact Me</h2>
    <form>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Me</a></li>
                <li><a href="skills.html">Skills</a></li>
                <li><a href="projects.html">Projects</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="home">
        <h2>Hello, I'm [Your Name]</h2>
        <p>Web Developer | Designer | Freelancer</p>
        <a href="contact.html" class="btn">Contact Me</a>
    </section>

    <footer>
        <p>© 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>

<section class="projects">
    <h2>My Projects</h2>
    <div class="project">
        <h3>Portfolio Website</h3>
        <p>A personal portfolio showcasing my skills.</p>
    </div>
</section>

<section class="skills">
    <h2>Skills & Resume</h2>
    <ul>
        <li>HTML, CSS, JavaScript</li>
        <li>React, Bootstrap</li>
        <li>Python, Django</li>
    </ul>
</section>
