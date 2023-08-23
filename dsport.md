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
            <a class="title-box" href="https://scelarek.github.io">Data Science Portfolio</a>
        </div>
        <hr>
        <!-- Entry 1: CovidCast -->
        <div class="project-content featured">
            <h2>Featured Project</h2>
            <h2><a href="/pages/covid.html" class="project-title">CovidCast: Predict to Protect</a></h2>
            <p class="skill-description">Time Series Forecasting &bull; Hyperparameter Tuning &bull; Feature Engineering &bull; Data Wrangling &bull; EDA</p>
            <p class="description">"Like a weather forecast for pandemics, COVIDCast leverages state-of-the-art machine learning and epidemiological models to deliver precise outbreak predictions."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/00381f16-48b4-4b64-bcb8-3df639dca68d" alt="COVIDCast Image">
        </div>
        <hr>
        <!-- Entry 2: SideBard -->
        <div class="project-content">
            <h2><a href="/pages/sidebard.html" class="project-title">SideBard for Google</a></h2>
            <p class="skill-description">Retrieval Augmented AI Text Generation &bull; LLMs &bull; Data Communication &bull; Hackathon &bull; Interdisciplinary Team</p>
            <p class="description">"Collaborated with my team, AInsight, of UX/UI, web devs, and data scientists to develop a figma prototype of a Chatbot in the Sidebar with Retrieval Augmented Generation for Google in 24hrs"</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/c92477af-6723-4dbf-b471-711889ed3808" alt="SideBard Image">
        </div>
        <hr>
        <hr>
        <!-- Entry 3: Puppularity Contest -->
        <div class="project-content">
            <h2><a href="/pages/twitter.html" class="project-title">Puppularity Contest</a></h2>
            <p class="skill-description">Web Scraping &bull; API &bull; Regression &bull; Classification</p>
            <p class="description">"Extracted "We Rate Dogs" tweets using API calls and BeautifulSoup, then evaluated comedic vs. aesthetic feature influence on engagement through regression models."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/f37fb5d6-2f11-48b3-8ebf-7328e7e13c28" alt="Twitter API Image">
        </div>
        <hr>
        <!-- Entry 4: Predicting Hotel Ratings from Reviews -->
        <div class="project-content">
            <h2><a href="/pages/hotel.html" class="project-title">Predicting Hotel Ratings from Reviews</a></h2>
            <p class="skill-description">Feature Engineering &bull; Classification &bull; NLP &bull; Hyperparameter Tuning</p>
            <p class="description">"Applied data preprocessing, feature engineering, NLP, and hyperparameter tuned classification models on 500,000+ hotel reviews to predict positive ratings at an accuracy of 78.4%."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/0db26b37-9d89-49d1-9900-0fe648e8215b" alt="Hotel Reviews Image">
        </div>
        <hr>
        <!-- Entry 5: West Nile Watch -->
        <div class="project-content">
            <h2><a href="/pages/wnv.html" class="project-title">West Nile Watch</a></h2>
            <p class="skill-description">Feature Engineering &bull; Data Wrangling &bull; EDA &bull; Hypothesis Testing</p>
            <p class="description">"Deployed hypothesis tests and classification models on 18,000+ entries to pinpoint West Nile Virus hotspots and high-risk species to guide community health interventions."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/dc1b5c27-eb6e-4f07-ac60-39734d601556" alt="West Nile Watch Image">
        </div>
        <hr>
        <!-- Entry 6: DS Templates and ML Guides -->
        <div class="project-content">
            <h2><a href="/pages/reference.html" class="project-title">DS Templates and ML Guides</a></h2>
            <p class="skill-description">Regression &bull; Classification &bull; Clustering &bull; Pipelines &bull; Grid Search</p>
            <p class="description">"Streamlined machine learning workflow using pipelines to grid search across the performance of various regression, classification, and clustering models on toy datasets."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/c8cbf178-a154-4637-9aae-9f55a7204c6a" alt="DS Templates Image">
        </div>
        <hr>
        <!-- Entry 7: Kickstarter -->
        <div class="project-content">
            <h2><a href="/pages/kickstart.html" class="project-title">Kickstarter: The Business Behind Dreams</a></h2>
            <p class="skill-description">SQL &bull; Data Wrangling &bull; EDA &bull; Classification</p>
            <p class="description">"Crafted a thorough business report using SQL, EDA, and classification models on 150,000+ entries to set viable fundraising targets for a tabletop board game campaign on Kickstarter."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/a07d8ef9-987d-45d5-8542-be7dbeee4a59" alt="Kickstarter Image">
        </div>
        <hr>
        <!-- Entry 8: Google Engrams -->
        <div class="project-content">
            <h2><a href="/pages/google.html" class="project-title">Google Engrams: Data in the Clouds</a></h2>
            <p class="skill-description">Hadoop &bull; AWS &bull; PySpark &bull; EDA</p>
            <p class="description">"Utilized the power of Hadoop, AWS, and PySpark on 260+ million entries in Google's corpus of books to analyze the frequency of the word 'data' over the past five hundred years."</p>
            <img class="featured-image" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/751e72f4-76bb-4628-b4bb-c07bcd602fe3" alt="Google Engrams Image">
        </div>
        <div>
            <p class="footer-quote">““The broader intellectual world seems to wildly overestimate how long it will take A.I. systems to go from ‘large impact on the world’ to ‘unrecognizably transformed world.’”<br>― Paul Christiano</p>
        </div>
    </section>
</body>
</html>
