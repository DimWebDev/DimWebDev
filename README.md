<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Personal GitHub Portfolio of DimWebDev">
    <title>DimWebDev - GitHub Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha384-k6RqeWeci5ZR/Lv4MR0sA0FfDOMyDpJSmBOAcqhm/Y5+Igjp4w5pJE5M+wh6BHG/" crossorigin="anonymous">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 2rem;
            text-align: center;
            width: 100%;
        }
        header img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        main {
            width: 80%;
            max-width: 800px;
            margin: 2rem 0;
        }
        h2 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 0.5rem;
        }
        .tech-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .tech {
            display: flex;
            align-items: center;
            margin: 0.5rem;
        }
        .tech i {
            font-size: 1.5rem;
            margin-right: 0.5rem;
            color: #4CAF50;
        }
        .project {
            margin: 1rem 0;
        }
        .project a {
            color: #4CAF50;
            text-decoration: none;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            width: 100%;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>DimWebDev</h1>
        <p>Software Engineer | Jurist | Lifelong Learner</p>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm a passionate software engineer. I love problem solving and I enjoy interpreting solutions into code. I believe that communication is the key. And by that, I mean communicating clearly with colleagues and stakeholders and also applying this in code writing with documentation, clean code, and self-documenting practices.</p>
            <h3>Technologies I Use</h3>
            <h4>Frontend</h4>
            <div class="tech-section">
                <div class="tech">
                    <i class="fab fa-react"></i>
                    <span>React</span>
                </div>
                <div class="tech">
                    <i class="fab fa-js-square"></i>
                    <span>JavaScript</span>
                </div>
                <div class="tech">
                    <i class="fab fa-css3-alt"></i>
                    <span>CSS</span>
                </div>
                <div class="tech">
                    <i class="fab fa-html5"></i>
                    <span>HTML</span>
                </div>
                <div class="tech">
                    <i class="fab fa-styled-components"></i>
                    <span>Styled Components</span>
                </div>
                <div class="tech">
                    <i class="fab fa-wordpress"></i>
                    <span>WordPress</span>
                </div>
                <div class="tech">
                    <i class="fas fa-code"></i>
                    <span>TypeScript</span>
                </div>
            </div>
            <h4>Backend</h4>
            <div class="tech-section">
                <div class="tech">
                    <i class="fab fa-java"></i>
                    <span>Java</span>
                </div>
                <div class="tech">
                    <i class="fas fa-server"></i>
                    <span>RESTful APIs</span>
                </div>
                <div class="tech">
                    <i class="fas fa-database"></i>
                    <span>SQL</span>
                </div>
                <div class="tech">
                    <i class="fas fa-database"></i>
                    <span>PostgreSQL</span>
                </div>
                <div class="tech">
                    <i class="fas fa-boxes"></i>
                    <span>Microservices</span>
                </div>
                <div class="tech">
                    <i class="fab fa-google"></i>
                    <span>Go</span>
                </div>
                <div class="tech">
                    <i class="fas fa-cloud"></i>
                    <span>Cloud Computing Principles</span>
                </div>
            </div>
            <h4>General Software Engineering Skills</h4>
<ul>
    <li>Problem Solving</li>
    <li>Problem Analysis</li>
    <li>Critical Thinking</li>
    <li>Logical Reasoning</li>
    <li>Thinking in Systems</li>
    <li>Organizational Skills</li>
    <li>Agile Methodologies</li>
    <li>Git Version Control</li>
</ul>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <h3>👉 👉 👉 Check my Pinned Repositories.</h3>
            <p>I have carefully selected them, because they are the latest pieces of my work. I tried to learn by doing and improving myself. I do not assume they are perfect but, who is? My goal is to track my progress, critic myself, and learn from what did not work in retrospect.</p>
        </section>
    </main>
    <footer>
        <h2>Contact</h2>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/dimitrios-liasis" target="_blank">DimWebDev</a></p>
    </footer>
</body>
</html>