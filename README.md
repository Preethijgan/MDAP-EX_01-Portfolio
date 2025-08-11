# MDAP-EX_01-Portfolio
## Date: 11-08-2025

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Preethi</h1>
        <p>Third-year Learner | Aspiring Developer</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <div class="about-container">
            <img src="asset.jpg" alt="Preethi Photo">
            <p>Hello! I'm Preethi, a passionate Third-year college learner with a love for technology, problem-solving, and creativity. I enjoy learning new skills and working on projects that challenge me.</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="card">HTML</div>
            <div class="card">CSS</div>
            <div class="card">Java</div>
            <div class="card">Python</div>
            <div class="card">JavaScript</div>
            <div class="card">C Programing</div>
            <div class="card">Problem Solving</div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>Student Grievance Portal</h3>
                <p>A web-based platform to register and track student grievances efficiently.</p>
            </div>
            <div class="card">
                <h3>Portfolio Website</h3>
                <p>Personal portfolio to showcase my skills, projects, and achievements.</p>
            </div>
        </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
<p>Email: <a href="mailto:preethijagan007@gmail.com">preethijagan007@gmail.com</a></p>
<div class="contact-links">
    <a href="https://www.linkedin.com/in/preethi-jagan-88a093282/" target="_blank">LinkedIn</a>
    <a href="https://github.com/Preethijgan" target="_blank">GitHub</a>
</div>


    <footer>
        <p>&copy; Preethi J(212223220080)</p>
    </footer>

</body>
</html>


```

style.css

```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: #f4f4f4;
    color: #333;
}

header {
    background: #4CAF50;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

header h1 {
    font-size: 2.5rem;
}

nav {
    background: #333;
    padding: 0.5rem;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

section {
    max-width: 900px;
    margin: auto;
    padding: 2rem;
}

h2 {
    margin-bottom: 1rem;
    color: #4CAF50;
}

.about-container {
    display: flex;
    align-items: center;
    gap: 2rem;
    flex-wrap: wrap;
}

.about-container img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
}

.skills, .projects {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 1rem;
    flex: 1 1 calc(33% - 1rem);
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    border-radius: 5px;
}

.contact-links a {
    display: inline-block;
    margin: 0.5rem 1rem 0 0;
    padding: 0.5rem 1rem;
    background: #4CAF50;
    color: white;
    border-radius: 5px;
    text-decoration: none;
}

.contact-links a:hover {
    background: #45a049;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}


```


## OUTPUT
<img width="1839" height="929" alt="image" src="https://github.com/user-attachments/assets/404414b7-36ef-43c7-ba29-cb97223ede5c" />
<img width="1835" height="922" alt="image" src="https://github.com/user-attachments/assets/cae11047-52cd-4225-a225-b322690fafdf" />






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
