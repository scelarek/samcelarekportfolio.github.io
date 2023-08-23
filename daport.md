<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset some default browser styles */
        body, h2, p {
            margin: 0;
            padding: 0;
        }
        /* Global styles */
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #fff;
            padding: 40px 20px;
            color: #333;
        }
        h2 {
            font-family: 'Poppins', sans-serif;
            text-align: center;
            color: #555;
            margin-bottom: 20px;
        }
        a {
            color: #007BFF;
            text-decoration: underline; /* Added underline to all links */
        }
        a:hover {
            text-decoration: underline;
            opacity: 0.9;
            transform: translateY(-3px); /* Added matching hover behavior */
        }
        .project-content {
            background-color: #E6FFF1;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            margin-bottom: 30px;
        }
        .project-description {
            font-size: 0.9em;
            margin: 5px 0;
        }
        .description {
            font-size: 0.9em;
            margin: 5px 0;
            background-color: #E0E0E0;
            padding: 20px;
            border-radius: 10px;
            font-weight: bold;
        }
        .skill-description {
            font-size: 0.8em;        /* Smaller text */
            font-weight: normal;     /* Non-bold font */
            text-align: center;     /* Centered text */
            background-color: transparent; /* No background */
            margin: 5px 0;
            padding: 10px;
            border-radius: 10px;
        }
        .view-project {
            display: inline-block;
            background-color: #25A18E;
            padding: 10px 10px;
            border-radius: 15px;
            color: white;
            font-weight: bold;
            margin: 10px 0;
            font-family: 'Poppins', sans-serif; /* Changed font for better legibility */
            transition: all 0.3s ease;
        }
        .view-project:hover {
            opacity: 0.9;
            transform: translateY(-3px); /* Matching hover behavior */
        }
        /* Styling for the Featured Project */
        .project-content.featured {
            background-color: #CFF2FB; 
        }
        .project-content.featured .view-project {
            background-color: #00A5CF; 
        }
        .project-content.featured h2 {
            color: #00A5CF; /* Added a different color for the Featured Project title */
        }
        .center-container {
            display: flex;
            justify-content: center; /* Horizontal centering */
            align-items: center;     /* Vertical centering */
        }
        .title-box {
            color: white;
            text-decoration: none;
            transition: transform 0.3s, opacity 0.3s;
            text-align: center;
            font-weight: bold;
            margin: 10px;
            padding: 10px 10px;
            border-radius: 10px;
            display: inline-block;
            font-size: 1.3em;
            background-color: #004e64ff;
        }
        .title-box:hover {
            opacity: 0.9;
            transform: translateY(-3px);
            text-decoration: underline; 
        }
        .footer-quote {
            text-align: center;
            background-color: #F3FFF8;
            padding: 20px;
            border-radius: 5px;
            margin-top: 30px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            font-style: italic;
        }
    </style>
</head>
<body>
    <section>
        <div class="center-container">
            <a class="title-box" href="https://scelarek.github.io">Data Analysis Portfolio</a>
        </div>
        <hr>
        <div class="project-content featured">
            <h2>Featured Project</h2>
            <h2><a href="/pages/google.html" class="project-title">Google Engrams: Data in the Clouds</a></h2>
            <p class="skill-description">Hadoop &bull; AWS &bull; PySpark &bull; EDA</p>
            <p class="description">Utilized Hadoop, AWS, and PySpark on 260+ million entries in Google's corpus of books to analyze the frequency of the word 'data' over the past five hundred years.</p>
            <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/751e72f4-76bb-4628-b4bb-c07bcd602fe3" alt="Google Engrams Image" class="featured-image">
        </div>
        <hr>
        <div class="project-content">
            <h2><a href="/pages/kickstart.html" class="project-title">Kickstarter: The Business Behind Dreams</a></h2>
            <p class="skill-description">SQL &bull; Data Wrangling &bull; EDA &bull; Classification</p>
            <p class="description">"Crafted a thorough business report using SQL, EDA, and classification models on 150,000+ entries to set viable fundraising targets for a tabletop board game campaign on Kickstarter."</p>
            <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/a07d8ef9-987d-45d5-8542-be7dbeee4a59" alt="Kickstarter Image" class="featured-image">
        </div>
        <hr>
        <div class="project-content">
            <h2><a href="pages/eternal.html" class="project-title">Eternal Growth, Immortal Inequality</a></h2>
            <p class="skill-description">Data Wrangling &bull; EDA &bull; Correlation Analysis</p>
            <p class="description">"Performed data tidying, feature engineering and EDA on Gapminder data to discern correlations between a nation's wealth, inequality, and well-being."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/2c8ec283-452c-448a-96d3-330932912d67" alt="Eternal Growth Image">
        </div>
        <hr>
        <div class="project-content">
            <h2><a href="/pages/global.html" class="project-title">Local vs Global Warming</a></h2>
            <p class="skill-description">SQL &bull; EDA &bull; Trend Analysis</p>
            <p class="description">"Analyzed historical global and city temperatures trends using SQL, Python, descriptive statistics, and employed linear regression to highlight patterns."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/209c121a-1bca-4d00-b70e-907fcd8d298c" alt="Global Warming Image">
        </div>
        <div>
            <p class="footer-quote">“The challenge for us is this: How can we ensure that, when we try to help others, we do so as effectively as possible?” <br> ― William Macaskill, Doing Good Better</p>
        </div>
    </section>
</body>
</html>
