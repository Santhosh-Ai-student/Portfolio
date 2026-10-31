# Ex01 Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Santhosh | Portfolio</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    
    <header>
        <nav>
            <h2 class="logo">Santhosh.</h2>

            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    
    <section id="home">

        <img src="images/profile.jpeg"
             alt="Santhosh Profile Photo"
             class="profile-img">

        <h1>Hello, I'm Santhosh</h1>

        <h3>AI & Data Science Student | Web Developer</h3>

        <p>
            I am passionate about technology, programming,
            artificial intelligence and web development.
        </p>

        <a href="#contact" class="btn">Contact Me</a>

    </section>

    
    <section id="about">

        <h2>About Me</h2>

        <p>
            I am a B.Tech Artificial Intelligence and Data Science
            student interested in building innovative technology
            solutions. I enjoy developing websites, exploring AI
            and learning new technologies.
        </p>

        <h3>My Skills</h3>

        <div class="skills">
            <span>Python</span>
            <span>JavaScript</span>
            <span>HTML</span>
            <span>CSS</span>
            <span>React</span>
            <span>SQL</span>
        </div>

    </section>

    
    <section id="projects">

        <h2>My Projects</h2>

        <div class="project-container">

            <div class="project-card">
                <h3>Portfolio Website</h3>
                <p>
                    A personal portfolio website built using
                    HTML and CSS.
                </p>
            </div>

            <div class="project-card">
                <h3>Todo Application</h3>
                <p>
                    A task management application developed
                    using JavaScript.
                </p>
            </div>

            <div class="project-card">
                <h3>AI Tour Planner</h3>
                <p>
                    An AI-powered application that helps users
                    plan their trips.
                </p>
            </div>

        </div>

    </section>

    
    <section id="contact">

        <h2>Contact Me</h2>

        <p>Email: santhoshsivakumar468@gmail.com</p>

        <p>
            GitHub:
            <a href="https://github.com/Santhosh-Ai-student"
               target="_blank">
                My GitHub
            </a>
        </p>

        <p>
            LinkedIn:
            <a href="https://www.linkedin.com/in/s-santhosh-3ba30636b/"
               target="_blank">
                My LinkedIn
            </a>
        </p>

    </section>

    
    <footer>
        <p>
            &copy; 2026 Santhosh. All Rights Reserved.
        </p>
    </footer>

</body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2026-10-31 154003.png>)
![alt text](<Screenshot 2026-10-31 154026.png>)

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
