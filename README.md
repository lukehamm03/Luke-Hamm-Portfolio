<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luke Hamm - Portfolio</title>
    <link rel="stylesheet" href="assets/css/custom.css"> <!-- Link to your custom CSS file -->
    <style>
        /* Styling for the resume link */
        a.resume-link {
            text-decoration: none;
            color: #333;  /* Original color */
            font-weight: bold;
            font-size: 18px;
        }

        a.resume-link:hover {
            color: #007BFF;  /* Change to blue on hover */
            transition: color 0.3s ease;
        }

        /* Basic styling for the project card */
        .project-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            margin: 15px 0;
            background-color: #f4f4f4;
            transition: transform 0.3s ease, background-color 0.3s ease;
        }

        /* On hover, the background color changes, and the project card "moves" slightly */
        .project-card:hover {
            background-color: #333;  /* Darker background */
            transform: translateY(-10px); /* Slight upward movement */
            cursor: pointer;
        }

        /* Styling for the project content inside the card */
        .project-card a {
            text-decoration: none;
            color: inherit;
        }

        /* Change text color when hovering over project cards */
        .project-card:hover .project-content h3, 
        .project-card:hover .project-content p {
            color: #fff; /* White text on hover */
        }

        /* Additional hover effect on the project link */
        .project-card a:hover {
            text-decoration: none;
        }
    </style>
</head>
<body>
    <h1>Luke Hamm - Portfolio</h1>
    
    <nav>
        <a href="#resume">Resume</a> | 
        <a href="#projects">Projects</a> | 
        <a href="#about">About Me</a>
    </nav>
    
    <section id="resume">
        <h2>Resume</h2>
        <!-- Resume link -->
        <a href="Luke_Hamm_Resume.pdf" target="_blank" class="resume-link">Resume</a>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        
        <div class="project-card">
            <a href="MLB_Salaries_Project.pdf" target="_blank">
                <div class="project-content">
                    <h3>MLB Salaries Project</h3>
                    <p>Conducted an in-depth analysis of the relationship between MLB player salaries and on-field performance using statistical methods like regression analysis. Processed and visualized extensive player data to identify key trends and highlight discrepancies between compensation and performance, contributing to discussions on team financial efficiency.</p>
                </div>
            </a>
        </div>

        <div class="project-card">
            <a href="Hackathon.pdf" target="_blank">
                <div class="project-content">
                    <h3>Reds Hackathon</h3>
                    <p>Collaborative advanced data analysis working with large data sets of MLB statistics. Used predictive modeling to estimate which pitchers would be better suited in a new role.</p>
                </div>
            </a>
        </div>

    </section>
    
    <section id="about">
        <h2>Skills</h2>
        <p>A R, Python, Excel.</p>
    </section>

    <!-- Contact section -->
    <footer>
        <h2>Contact</h2>
        <ul>
            <li><a href="https://www.linkedin.com/in/luke-hamm-93ab3527b" target="_blank">LinkedIn</a></li>
            <li><a href="https://github.com/lukehamm03" target="_blank">GitHub</a></li>
            <li><a href="mailto:lukehamm03@gmail.com">Email Me</a></li>
        </ul>
    </footer>
</body>
</html>
