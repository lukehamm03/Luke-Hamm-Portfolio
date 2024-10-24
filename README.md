<style>
    /* Centering the resume and LinkedIn container */
    .resume-linkedin-container {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px; /* Space between the Resume and LinkedIn */
        margin: 20px auto;
    }

    /* Styling for the resume box */
    .resume-box {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100px; /* Adjust height for smaller size */
        width: 150px;  /* Adjust width for smaller size */
        border: 2px solid #ddd;
        border-radius: 8px;
        background-color: #f4f4f4;
        transition: background-color 0.3s ease, color 0.3s ease;
        text-align: center;
        cursor: pointer;
    }

    /* Resume box hover effect */
    .resume-box:hover {
        background-color: #007BFF;  /* Blue background on hover */
        color: #fff;  /* White text on hover */
    }

    /* Styling for the text inside the resume box */
    .resume-box a {
        text-decoration: none;
        color: inherit;  /* Inherit color, including the hover color */
        font-size: 24px;  /* Larger font size */
        font-weight: bold; /* Bold text */
    }

    /* Styling for the LinkedIn logo */
    .linkedin-logo {
        width: 50px; /* Adjust the size of the LinkedIn logo */
        cursor: pointer;
        transition: transform 0.3s ease;
    }

    /* Hover effect for LinkedIn logo */
    .linkedin-logo:hover {
        transform: scale(1.1); /* Slightly enlarge on hover */
    }

    /* Project card styling */
    .project-card {
        border: 1px solid #ddd;
        border-radius: 8px;
        padding: 20px;
        margin: 15px 0;
        background-color: #f4f4f4;
        transition: transform 0.3s ease, background-color 0.3s ease;
        position: relative; /* To position the logos inside the card */
        max-width: 900px; /* Set a max-width to reduce white space */
        margin-left: auto;
        margin-right: auto; /* Center content and reduce white space */
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

    /* Download icon positioning and styling */
    .download-icon {
        position: absolute;
        top: 10px;
        right: 10px;
        width: 30px;
        height: 30px;
        cursor: pointer;
        transition: transform 0.3s ease;
    }

    /* Scale effect on hover for download icons */
    .download-icon:hover {
        transform: scale(1.1);
    }

    /* Adjust the size of the logos if necessary */
    .download-icon img {
        width: 100%;
        height: auto;
    }

    /* Center the skills section heading */
    #about h2 {
        text-align: center;
        margin-bottom: 20px;
    }

    /* Styling for the skills boxes */
    .skills-container {
        display: flex;
        justify-content: center;
        gap: 20px; /* Space between the skill boxes */
    }

    .skill-box {
        border: 2px solid #ddd;
        border-radius: 8px;
        padding: 10px 20px;
        background-color: #f4f4f4;
        font-size: 18px;
        font-weight: bold;
        text-align: center;
        width: 100px; /* Adjust width to keep the boxes consistent */
        transition: background-color 0.3s ease, transform 0.3s ease;
    }

    /* Hover effect for the skill boxes */
    .skill-box:hover {
        background-color: #007BFF;
        color: white;
        transform: scale(1.05); /* Slight scale-up on hover */
    }
</style>

<!-- Resume and LinkedIn Section -->
<section id="resume-linkedin">
    <div class="resume-linkedin-container">
        <!-- Resume box -->
        <a href="Resume.pdf" target="_blank">
            <div class="resume-box">
                Resume
            </div>
        </a>
        
        <!-- LinkedIn logo -->
        <a href="https://www.linkedin.com/in/luke-hamm-93ab3527b" target="_blank">
            <img src="LinkedIn-logo.png" alt="LinkedIn" class="linkedin-logo">
        </a>
    </div>
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
        <!-- R logo for downloading the R code -->
        <a href="https://github.com/lukehamm03/Luke-Hamm-Portfolio/blob/main/MLBSlaraiesCode.Rmd" download class="download-icon">
            <img src="R-logo.jpg" alt="Download R Code">
        </a>
    </div>

    <div class="project-card">
        <a href="Hackathon.pdf" target="_blank">
            <div class="project-content">
                <h3>Reds Hackathon</h3>
                <p>Collaborative advanced data analysis working with large data sets of MLB statistics. Used predictive modeling to estimate which pitchers would be better suited in a new role.</p>
            </div>
        </a>
        <!-- R logo for downloading the R code -->
        <a href="https://github.com/lukehamm03/Luke-Hamm-Portfolio/blob/main/RedsHackathon%20(1).Rmd" download class="download-icon">
            <img src="R-logo.jpg" alt="Download R Code">
        </a>
    </div>

    <div class="project-card">
        <a href="Unit_1_Project.pdf" target="_blank">
            <div class="project-content">
                <h3>Fantasy Football Player Value</h3>
                <p>Developed an analytical tool using historical NFL data to assess fantasy football player performance, tracking week-by-week trends to determine how long a player must consistently over- or under-perform to justify reassessing their value. The analysis leverages statistical methods to offer insights for decision-making in player trades, adds, or drops.</p>
            </div>
        </a>
        <!-- Python logo for downloading the Python code -->
        <a href="https://github.com/lukehamm03/Luke-Hamm-Portfolio/blob/main/fantasyplayervaluecode.ipynb" download class="download-icon">
            <img src="Python-logo.jpg" alt="Download Python Code">
        </a>
    </div>
</section>

<!-- About Section -->
<section id="about">
    <h2>Skills</h2>
    <div class="skills-container">
        <div class="skill-box">R</div>
        <div class="skill-box">Python</div>
        <div class="skill-box">Excel</div>
    </div>
</section>
