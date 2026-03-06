# profile
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gowtham Shankar | Portfolio</title>
<h1>Portfolio Website</h1>

<style>
html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f6f9;
    color: #333;
    transition: 0.4s;
}

.dark-mode {
    background: #0f172a;
    color: #f1f5f9;
}

header {
    background: #0f172a;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

header button {
    margin-top: 15px;
    padding: 8px 15px;
    border: none;
    background: #38bdf8;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}

nav {
    background: #1e293b;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

section {
    padding: 60px 10%;
}

h2 {
    border-left: 5px solid #38bdf8;
    padding-left: 10px;
}

.skills span {
    display: inline-block;
    background: #38bdf8;
    color: white;
    padding: 8px 12px;
    margin: 5px;
    border-radius: 5px;
}

.project-card {
    background: white;
    padding: 20px;
    margin: 15px 0;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.dark-mode .project-card {
    background: #1e293b;
}

.download-btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #0f172a;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 20px;
    background: #0f172a;
    color: white;
}
</style>
</head>

<body>

<header>
    <h1>Gowtham Shankar</h1>
    <p>Computer Science Intern | Web Developer</p>
    <button onclick="toggleDarkMode()">Toggle Dark Mode</button>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>I am a passionate Computer Science intern interested in web development and software development.</p>
    <p>I am currently pursuing my degree in computer science</p>
    <p>I am very in learning new skills and gaining practical knowledge</p>
    <p>I am a quick learner and hard working </p>
    <p>I am very exicted to improve my skills soon</p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills">
        <span><a href="https://www.w3schools.com/html/">HTML</a></span>
        <span><a href="https://www.w3schools.com/css/">CSS</a></span>
        <span><a href="https://www.w3schools.com/javascript">JAVASCRIPT</a></span>
        <span><a href="https://www.w3schools.com/python">PYTHON</a></span>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project-card">
        <h3>Resume Generator</h3>
        <p>A dynamic resume generator website.</p>
    </div>

    <div class="project-card">
        <h3>To-Do List App</h3>
        <p>A task manager with local storage.</p>
    </div>

    <!-- Download Resume Button -->
    <a href="resume.pdf" download class="download-btn">Download My Resume</a>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: gowthamshankar454@gmail.com</p>
</section>

<footer>
    <p>© 2026 Shankar | All Rights Reserved</p>
</footer>

<script>
function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
}
</script>

</body>
</html# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
