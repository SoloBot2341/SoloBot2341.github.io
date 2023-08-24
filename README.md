<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Welcome To My Portfolio</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Jermaine Miller. This is a brief introduction about myself.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <!-- Sample project -->
        <div class="project-card">
            <h3>Game Creation</h3>
            <p> In my first few months of programming I learned a lot with games.
                In these projects I used pygame to build a 2d fighter game and a Connect Four game. </p><br>
                <p> -- 2d fighter <a href="https://github.com/SoloBot2341/Greatest-Brawler-Game">View on GitHub</a></p>
                <p> -- Connect Four  <a href="https://github.com/SoloBot2341/Everyday-projects/blob/main/Solo_connect_four.py">View on GitHub</a></p> 
        </div>

        <div class="project-card">
            <h3>Ai image recognition </h3>
            <p>Ai has gotten a lot of hype lately so I jumped ship and gave it a shot. 
                I used frameworks such as Kera for datasets, numpy and matplotlib to design a basic image recognition ai. </p><br>

                <p> -- Ai Image Recognition <a href="https://github.com/SoloBot2341/Everyday-projects/blob/main/python_vending_machine.py">View on GitHub</a></p>

        </div>

        <div class="project-card">
            <h3> Vending Machine Simulation </h3>
            <p>A common way I practice programming is to build simulations, Here I decided to build a vending machine simulation 
                with tkinkter and basic threading. </p><br>
                <p> -- Vending Machine  <a href="https://github.com/SoloBot2341/Everyday-projects/blob/main/python_vending_machine.py">View on GitHub</a></p> 
        </div>

        <div class="project-card">
            <h3>Static Sales Website</h3>
            <p> During a intership I took a web development course focusing on css and html, I managed to build a static sales Website
                for my final project. </p>
                <p> -- Sales Website  <a href="https://github.com/SoloBot2341/FinalProject_webpage">View on GitHub</a></p> 
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>My Email: <a href="mailto:jermainemiller2341@gmail.com">jermainemiller2341@gmail.com</a></p>
        <p>My Linkedin <a href="https://www.linkedin.com/in/jermaine-miller-982394208/"> linkedin</a></p>
    </section>

    <footer>
        <p>Copyright © 2023 Jermaine</p>
    </footer>
</body>
</html>
