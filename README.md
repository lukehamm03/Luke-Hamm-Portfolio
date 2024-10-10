<style>
    /* Centering the resume box on the page */
    .resume-box {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 200px; /* Adjust height as necessary */
        width: 300px;  /* Adjust width as necessary */
        margin: 50px auto;
        border: 2px solid #ddd;
        border-radius: 8px;
        background-color: #f4f4f4;
        transition: background-color 0.3s ease, color 0.3s ease;
        text-align: center;
        cursor: pointer;
    }

    /* Resume box hover effect (turns blue) */
    .resume-box:hover {
        background-color: #007BFF;  /* Blue background on hover */
        color: #fff;  /* White text on hover */
    }

    /* Styling for the text inside the box */
    .resume-box a {
        text-decoration: none;
        color: inherit;  /* Inherit color, including the hover color */
        font-size: 20px;
        font-weight: bold;
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

<!-- Resume Section -->
<section id="resume">
    <a href="Luke_Hamm_Resume.pdf" target="_blank">
        <div class="resume-box">
            View My Resume
        </div>
    </a>
</section>

<!-- Projects Section -->
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

    <div class="project-card">
        <a href="Unit_1_Project.pdf" target="_blank">
            <div class="project-content">
                <h3>Fantasy Football Player Value</h3>
                <p>Developed an analytical tool using historical NFL data to assess fantasy football player performance, tracking week-by-week trends to determine how long a player must consistently over- or under-perform to justify reassessing their value. The analysis leverages statistical methods to offer insights for decision-making in player trades, adds, or drops.</p>
            </div>
        </a>
    </div>
</section>

<!-- About Section -->
<section id="about">
    <h2>Skills</h2>
    <p>R, Python, Excel.</p>
</section>

<!-- Contact Section -->
<footer>
    <h2>Contact</h2>
    <ul>
        <li><a href="https://www.linkedin.com/in/luke-hamm-93ab3527b" target="_blank">LinkedIn</a></li>
        <li><a href="https://github.com/lukehamm03" target="_blank">GitHub</a></li>
        <li><a href="mailto:lukehamm03@gmail.com">Email Me</a></li>
    </ul>
</footer>
