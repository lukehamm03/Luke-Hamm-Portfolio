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
    .resume-box, .linkedin-box {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100px; /* Set consistent height */
        width: 150px;  /* Set consistent width */
        border: 2px solid #ddd;
        border-radius: 8px;
        background-color: #f4f4f4;
        transition: background-color 0.3s ease, color 0.3s ease, transform 0.3s ease;
        text-align: center;
        cursor: pointer;
    }

    /* Hover effect for the resume and LinkedIn boxes */
    .resume-box:hover, .linkedin-box:hover {
        background-color: #007BFF;  /* Blue background on hover */
        color: #fff;  /* White text on hover */
        transform: scale(1.05); /* Slightly enlarge on hover */
    }

    /* Styling for the text inside the resume box */
    .resume-box a {
        text-decoration: none;
        color: inherit;  /* Inherit color, including the hover color */
        font-size: 24px;  /* Larger font size */
        font-weight: bold; /* Bold text */
    }

    /* Styling for the LinkedIn logo inside the box */
    .linkedin-box img {
        width: 40px; /* Set the size of the LinkedIn logo */
        height: auto;
    }
</style>

<!-- Resume and LinkedIn Section -->
<section id="resume-linkedin">
    <div class="resume-linkedin-container">
        <!-- Resume box -->
        <a href="Luke_Hamm_Resume.pdf" target="_blank">
            <div class="resume-box">
                Resume
            </div>
        </a>
        
        <!-- LinkedIn box -->
        <a href="https://www.linkedin.com/in/luke-hamm-93ab3527b" target="_blank">
            <div class="linkedin-box">
                <img src="LinkedIn-logo.png" alt="LinkedIn">
            </div>
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
