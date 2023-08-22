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
        .project-content:first-child {
            background-color: #CFF2FB; /* Changed the background color for the Featured Project */
        }
        .project-content:first-child .view-project {
            background-color: #00A5CF; /* Changed the background color for the Featured Project's view project link */
        }
    </style>
</head>

<body>
    <section>
        <div class="project-content">
            <h2><a href="/pages/covid.html" class="view-project">Featured Project: CovidCast</a></h2>
            <p class="project-description">Like a weather forecast for pandemics, COVIDCast leverages state-of-the-art machine learning and epidemiological models to deliver precise outbreak predictions.</p>
            <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/00381f16-48b4-4b64-bcb8-3df639dca68d" alt="COVIDCast Image" style="max-width: 100%; border-radius: 10px; margin-top: 20px;">
        </div>
        <div class="project-content">
            <h2><a href="/dsport.html" class="view-project">Data Science Portfolio</a></h2>
            <p class="project-description">Time Series Forecasting &bull; Hyperparameter Tuning &bull; Feature Engineering &bull; Web Scraping &bull; Regression &bull; Classification &bull; Clustering &bull; Deep Learning &bull; NLP &bull; Pipelines &bull; Grid Search &bull; Retrieval Augmented AI Text Generation &bull; LLMs </p>
        </div>
        <div class="project-content">
            <h2><a href="/daport.html" class="view-project">Data Analysis Portfolio</a></h2>
            <p class="project-description">Databases &bull; SQL &bull; Data Wrangling &bull; Data Cleaning &bull; Cloud Computation &bull; EDA &bull; Descriptive Statistics &bull; Time Series Analysis &bull; Tableau &bull; Dashboards &bull; Business Reports &bull; Data Visualization </p>
        </div>
        <div class="project-content">
            <h2><a href="https://portlandear.wordpress.com/" class="view-project">Effective Altruism Portfolio</a></h2>
            <p class="project-description">Community Building &bull; Leadership &bull; Agenda Setting &bull; Volunteer Work &bull; Presentations &bull; Outreach &bull; Philosophy &bull; Economics &bull; Research</p>
        </div>
    </section>
</body>

</html>
