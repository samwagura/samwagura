<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel Wagura Njuguna - Frontend Developer</title>
    <style>
        :root {
            --primary: #881F42;
            --secondary: #E3A842;
            --accent: #4A8E7C;
            --dark: #2D2926;
            --light: #F8F5F0;
            --gray: #6a737d;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid var(--secondary);
            margin-bottom: 30px;
        }
        
        h1 {
            color: var(--primary);
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: var(--primary);
            margin: 25px 0 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--secondary);
        }
        
        h3 {
            color: var(--primary);
            margin: 20px 0 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: var(--gray);
            margin-bottom: 20px;
        }
        
        .highlight {
            background: linear-gradient(120deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            margin: 25px 0;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        
        .skill {
            background-color: var(--primary);
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .learning {
            background-color: var(--secondary);
        }
        
        .project {
            background-color: white;
            border: 1px solid #e1e4e8;
            border-left: 4px solid var(--primary);
            border-radius: 6px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        
        .project h3 {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .project-links a {
            color: var(--primary);
            text-decoration: none;
            margin-left: 15px;
            font-weight: 500;
        }
        
        .project-links a:hover {
            text-decoration: underline;
        }
        
        .stats {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin: 30px 0;
            flex-wrap: wrap;
        }
        
        .stat-item {
            padding: 15px;
            min-width: 150px;
        }
        
        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            color: var(--primary);
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
            flex-wrap: wrap;
        }
        
        .contact-links a {
            color: var(--primary);
            text-decoration: none;
            font-weight: 500;
            padding: 8px 16px;
            border: 2px solid var(--primary);
            border-radius: 30px;
            transition: all 0.3s ease;
        }
        
        .contact-links a:hover {
            background-color: var(--primary);
            color: white;
            text-decoration: none;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #e1e4e8;
            color: var(--gray);
            font-size: 0.9rem;
        }
        
        .learning-path {
            background-color: rgba(226, 167, 66, 0.1);
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }
        
        @media (max-width: 768px) {
            .stats {
                flex-direction: column;
            }
            
            .project h3 {
                flex-direction: column;
                align-items: flex-start;
            }
            
            .project-links {
                margin-top: 10px;
            }
            
            .contact-links {
                flex-direction: column;
                align-items: center;
            }
            
            .contact-links a {
                width: 200px;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Samuel Wagura Njuguna</h1>
        <p class="tagline">ALX Frontend Developer | Building Results-Driven Websites for Impact-Driven Organizations</p>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <div class="highlight">
            <p>I'm an aspiring frontend developer currently learning through the ALX program, passionate about building websites that are not just visually stunning but deliver measurable results. My journey into software engineering began with a desire to become a solution provider for meaningful causes.</p>
            <p>With a background in graphic design, I bring a strong visual sensibility to my development work. I'm specializing in creating user-centric web experiences that help impact-driven businesses and organizations achieve their goals and make a difference in the world.</p>
        </div>
    </section>
    
    <section id="skills">
        <h2>Technical Skills</h2>
        <div class="skills-container">
            <span class="skill">HTML5</span>
            <span class="skill">CSS3</span>
            <span class="skill">JavaScript</span>
            <span class="skill learning">React (Learning)</span>
            <span class="skill">Responsive Design</span>
            <span class="skill">UI/UX Principles</span>
            <span class="skill">Git & GitHub</span>
            <span class="skill">Figma</span>
            <span class="skill">Adobe Creative Suite</span>
        </div>
    </section>
    
    <section id="learning">
        <h2>My Learning Journey</h2>
        <div class="learning-path">
            <p>I'm currently expanding my skills through the ALX Frontend Development program, focusing on:</p>
            <ul>
                <li>Mastering modern JavaScript frameworks (React, Vue)</li>
                <li>Advanced CSS techniques and preprocessors</li>
                <li>Web performance optimization</li>
                <li>Accessibility best practices</li>
                <li>Building responsive, mobile-first websites</li>
            </ul>
        </div>
    </section>
    
    <section id="projects">
        <h2>Learning Projects</h2>
        
        <div class="project">
            <h3>
                <span>Portfolio Website</span>
                <div class="project-links">
                    <a href="https://github.com/samwagura/portfolio" target="_blank">GitHub</a>
                </div>
            </h3>
            <p>A responsive portfolio website built with HTML, CSS, and JavaScript to showcase my projects and skills as I continue learning frontend development.</p>
            <div class="skills-container">
                <span class="skill">HTML5</span>
                <span class="skill">CSS3</span>
                <span class="skill">JavaScript</span>
            </div>
        </div>
        
        <div class="project">
            <h3>
                <span>ALX Practice Projects</span>
                <div class="project-links">
                    <a href="https://github.com/samwagura" target="_blank">GitHub</a>
                </div>
            </h3>
            <p>A collection of small projects and exercises completed as part of the ALX Frontend Development program, demonstrating my growing proficiency in web development.</p>
            <div class="skills-container">
                <span class="skill">HTML5</span>
                <span class="skill">CSS3</span>
                <span class="skill">JavaScript</span>
            </div>
        </div>
        
        <div class="project">
            <h3>
                <span>Design to Code Challenges</span>
                <div class="project-links">
                    <a href="https://www.behance.net/Samuel_Wagura" target="_blank">Behance</a>
                </div>
            </h3>
            <p>Converting UI/UX designs into functional web pages to practice implementation skills and bridge the gap between design and development.</p>
            <div class="skills-container">
                <span class="skill">UI/UX Design</span>
                <span class="skill">HTML5</span>
                <span class="skill">CSS3</span>
            </div>
        </div>
    </section>
    
    <section id="goals">
        <h2>Future Goals</h2>
        <p>I'm passionate about using my frontend development skills to create digital solutions for:</p>
        <ul>
            <li>Non-profit organizations making a social impact</li>
            <li>Sustainable businesses and eco-friendly initiatives</li>
            <li>Educational platforms and learning resources</li>
            <li>Community health and wellness applications</li>
        </ul>
    </section>
    
    <section id="stats">
        <h2>My Journey in Numbers</h2>
        <div class="stats">
            <div class="stat-item">
                <div class="stat-number">50+</div>
                <div class="stat-label">Hours of Learning</div>
            </div>
            <div class="stat-item">
                <div class="stat-number">10+</div>
                <div class="stat-label">Projects Completed</div>
            </div>
            <div class="stat-item">
                <div class="stat-number">100%</div>
                <div class="stat-label">Dedication to Growth</div>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Let's Connect</h2>
        <p>I'm always interested in connecting with other developers and discussing opportunities to contribute to meaningful projects as I continue my learning journey.</p>
        <div class="contact-links">
            <a href="mailto:samwagura@gmail.com">Email</a>
            <a href="https://www.linkedin.com/in/samwagura/" target="_blank">LinkedIn</a>
            <a href="https://x.com/samwagura" target="_blank">Twitter</a>
            <a href="https://www.behance.net/Samuel_Wagura" target="_blank">Design Portfolio</a>
        </div>
    </section>
    
    <footer>
        <p>© 2023 Samuel Wagura Njuguna. Passionate about creating web solutions that make a difference.</p>
    </footer>
</body>
</html>
