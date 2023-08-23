<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body, h2, p {
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f5f5f5;
            color: #333;
            padding: 40px 20px;
        }
        a {
            color: #007BFF;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .content-box {
            background-color: #E6FFF1;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            margin-bottom: 30px;
        }
        .description {
            font-size: 0.9em;
            margin: 10px 0;
            background-color: #f2f2f2;
            padding: 15px;
            border-radius: 10px;
        }
        .view-project {
            display: inline-block;
            background-color: #5DA46B;
            padding: 10px 20px;
            border-radius: 10px;
            color: white;
            font-weight: bold;
            margin: 10px 0;
            transition: all 0.3s ease;
        }
        .view-project:hover {
            opacity: 0.8;
        }
        .featured-image {
            max-width: 100%;
            border-radius: 10px;
            margin-top: 20px;
        }
        #name-box {
            text-align: center;
            font-weight: bold;
            color: white;
            margin: 20px 0;
            background-color: #004e64ff;
            border-radius: 10px;
            padding: 15px 20px;
            display: inline-block;
        }
        .skill-description {
            font-size: 0.8em;
            text-align: center;
            background-color: transparent;
            margin: 5px 0;
            padding: 10px;
            border-radius: 10px;
        }
        .expand-btn {
            background-color: #5da46bff;
            color: white;
            padding: 5px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            margin-top: 10px;
            outline: none;
            border: none;
        }
        .project-title {
            display: inline-block;
            background-color: #25A18E;
            padding: 10px 20px;
            border-radius: 10px;
            color: white;
            font-weight: bold;
            margin: 10px 0;
            font-family: 'Poppins', sans-serif;
            transition: all 0.3s ease;
        }
        .project-title:hover {
            opacity: 0.9;
            transform: translateY(-3px);
        }
        .project-content:first-child {
            background-color: #CFF2FB;
            box-shadow: 0 2px 20px rgba(0, 123, 255, 0.25);
        }
        .project-content:first-child .project-title {
            background-color: #00A5CF;
        }
    </style>
</head>

<body>
    <section>
        <div id="name-box">Data Analysis Portfolio</div>
        <hr>
        <div class="project-content content-box">
            <h2><a href="/pages/google.html" class="project-title">Featured Project: Google Engrams: Data in the Clouds</a></h2>
            <p class="skill-description">Hadoop &bull; AWS &bull; PySpark &bull; EDA</p>
            <p class="description">Utilized Hadoop, AWS, and PySpark on 260+ million entries in Google's corpus of books to analyze the frequency of the word 'data' over the past five hundred years.</p>
            <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/751e72f4-76bb-4628-b4bb-c07bcd602fe3" alt="Google Engrams Image" class="featured-image">
        </div>
        <hr>
        <div class="content-box">
            <h2><a href="/pages/kickstart.html" class="project-title">Kickstarter: The Business Behind Dreams</a></h2>
            <p class="skill-description">SQL &bull; Data Wrangling &bull; EDA &bull; Classification</p>
            <p class="description">"Crafted a thorough business report using SQL, EDA, and classification models on 150,000+ entries to set viable fundraising targets for a tabletop board game campaign on Kickstarter."</p>
            <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/a07d8ef9-987d-45d5-8542-be7dbeee4a59" alt="Kickstarter Image" class="featured-image">
        </div>
        <hr>
        <div class="content-box">
            <h2><a href="pages/eternal.html" class="project-title">Eternal Growth, Immortal Inequality</a></h2>
            <p class="skill-description">Data Wrangling &bull; EDA &bull; Correlation Analysis</p>
            <p class="description">"Performed data tidying, feature engineering and EDA on Gapminder data to discern correlations between a nation's wealth, inequality, and well-being."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/2c8ec283-452c-448a-96d3-330932912d67" alt="Eternal Growth Image">
        </div>
        <hr>
        <div class="content-box">
            <h2><a href="/pages/global.html" class="project-title">Local vs Global Warming</a></h2>
            <p class="skill-description">SQL &bull; EDA &bull; Trend Analysis</p>
            <p class="description">"Analyzed historical global and city temperatures trends using SQL, Python, descriptive statistics, and employed linear regression to highlight patterns."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/209c121a-1bca-4d00-b70e-907fcd8d298c" alt="Global Warming Image">
        </div>
    </section>
</body>
</html>
