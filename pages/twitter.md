<div align="center">

<h1>Puppularity Contest</h1>

<img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/f3d6abc1-b49e-42f6-b964-8a36e4381d3b" title="Puppularity Contest" alt="Puppularity Contest" width="150" height="150">


<h2><strong>By Sam Celarek</strong></h2>

</div>

<div align="center" style="background-color: #CCCCD6; padding: 15px; border-radius: 10px;">
"How might use machine learning to identify the factors that drive engagement for a popular Twitter account dedicated to comedic dog pictures and ratings?"
</div>


## 🎯 Project Overview

In this project, we delve into the 'We Rate Dogs' Twitter account to discern which aspects of the tweets, be it comedic or aesthetic, primarily drive user engagement. We employ multiple linear regressions, focusing first on a model with only comedic features as predictors, then on aesthetic attributes, and finally a combination of both. The target variable for these models is going to be a proxy for engagement called 'popularity rating', calculated as the sum of retweets and favorites. After all this, I then assess the magnitude and significance of each variable's impact on the popularity rating. 

## 📊 Dataset

The primary dataset for this analysis was sourced from the 'We Rate Dogs' Twitter account using the Twitter API. It contains detailed tweet data, including tweet text, user data, retweet count, favorite count, and other meta information. I also used a dataset with neural network classifications of each dog picture from the 'We Rate Dogs' tweet into its respective dog breed. 

## 🧹 Data Wrangling

The initial dataset from the Twitter API was in JSON format and several preprocessing steps were performed:
- **Beautiful Soup:** Extracted necessary fields from the raw JSON data and converted into a pandas DataFrame
- **Extensive Cleaning:** Cleaned dataframe with 13 different steps, removing any non-relevant meta information
- **Regex:** Parsed dog ratings, monikers, and names from the tweet text

## 🛠️ Feature Engineering

To prepare for the modeling phase, several new features were engineered in addition to the features already extracted from the tweet text. Also the target feature of `Popularity Rating` was created by summing retweets and favorites for each tweet.

- Text length of tweets as a new column
- Breeds were one-hot-encoded
- Time of day the tweet was posted
- **Target Variable:** Popularity Rating = retweets + favorites

## 📶 Exploratory Data Analysis (EDA)

EDA was performed to understand the underlying patterns in the data:

- Univariate Distribution of retweet count, favorite count, time of day, and neural net confidence level was explored
- Popularity Rating was plotted over over time.

In the time line plot below, it is notable that popularity rating steadily increases over time. This means that time passing, which is represented by the feature `dates_number`, is going to be very important in my model. This is likely because it serves as a proxy for the constantly increasing amount of followers that the 'We Rate Dogs' account has on twitter, which I unfortunately did not have access to in the available datasets. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/ed6f8d2a-f864-4873-a1cf-cb1f0285e7ae)

## 🖥️ Modeling

Three multiple linear regression models with different sets of features were trained to predict popularity rating. One MLR model had comedic features, another had aesthetic features, and the final had all features. Then the significance and effect size of each feature was assessed in each model. To summarize the findings, graph highlights the statistically significant variables in the all-features model. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/1f472f5c-6a87-4297-a4ac-641376ddfac1)

As we can see, the ratings of 14/10 and 13/10 have the most significant impact of the categorical features in the model compared to the baseline rating of 11/10. It would also appear that the monikers 'Puppo' and 'Doggo' drive higher levels of engagement too. Finally we can see here that breeds which were not frequently posted enough (>30 times) or hard for the neural net to recognize, did not generate as high of popularity ratings compared to the baseline dog breed of 'not dogs'.

## 📈 Discussion

From the analysis and modeling, several key insights were derived:
- **Comedic Model** | R-Squared= 0.37: The comedic model was the most predictive model and tweets with higher dog ratings tend to get more retweets and favorites. 
- **Aesthetic Model** | R-Squared= 0.32: No dog breed was statistically significant, however the nickname `doggo` and `puppo` had a positive impact on popularity. 
- **All Features Model** | R-Squared= 0.38: Time passing (`date_number`) was a very important variable to have in the model as popularity Ratings rise dramatically over time as the account gets more fans and followers. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/00a1a5f8-7b97-4417-9542-f67e1a660f92)

In conclusion, comedic features drive the more engagement than aesthetic ones, however this model only weeakly explains the variance in popularity meaning there is likely other latent (unmeasured) factors which contribute to popularity rating. 

<div align="center">

Best Wishes, <br>
Sam Celarek

</div>

---

## 💡 Other Resources

- **[Full Github Repository](https://github.com/scelarek/Puppularity-Contest)**
- **[Link to the Jupyter Wrangling Notebook](https://github.com/scelarek/Puppularity-Contest/blob/main/Twitter_Wrangle.ipynb)**
- **[Link to the Final Report dataset](https://github.com/scelarek/Puppularity-Contest/blob/main/Twitter_Insights.ipynb)**
- **[Link to the master dataset](https://github.com/scelarek/Puppularity-Contest/blob/main/Data/twitter_archive_master.csv)**
- **[Twitter API documentation](https://developer.twitter.com/en/docs)**
