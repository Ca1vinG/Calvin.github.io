<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #666;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            background-color: #fff;
            border-radius: 5px;
            max-width: 800px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio website. My name is Calvin. I am a senior in mechanical engineering.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <p>Here are some of my recent projects:</p>
        <ul>
            <li>Project 1: Design Department Member</li>
            <li>Project 2: Founder of LDW Music Bar</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me at: myemail@example.com</p>
    </section>
    <footer>
        &copy; 2024 My Portfolio
    </footer>
</body>
</html>
