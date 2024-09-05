# Code_Alpha_Portfolio
**#HTML Code**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pavan Av - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Pavan AV</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Pavan AV, an MCA student at Acharya Institute of Graduate Studies, with a strong interest in web development and IoT. Welcome to my portfolio.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
            <li>Python</li>
            <li>IoT</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Gesture Control Virtual Mouse</h3>
            <p>A project using machine learning to control a virtual mouse through gestures.</p>
        </div>
        <div class="project">
            <h3>IoT-based Mini Project</h3>
            <p>An IoT project focusing on [your project's objective].</p>
        </div>
    </section>

    <section id="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" download>Download My Resume</a>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form> 
    </section>

    <footer>
        <p>&copy; 2024 Pavan AV</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
                                                           **CSS Style Sheet**
        body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px;
    background: #fff;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form input, form textarea {
    display: block;
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
}

button {
    background: #333;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background: #555;
}
                                                                ** JS CODE**
       document.querySelector('form').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Message sent! Thank you for reaching out.');
});
                                                         

