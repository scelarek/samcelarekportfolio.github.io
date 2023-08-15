
<div align="center">

# Pupularity Contest

</div>

<div align="center" style="background-color: #CCCCD6; padding: 15px; border-radius: 10px;">
"How might use machine learning to identify the factors that drive engagement for a popular Twitter account dedicated to comedic dog pictures and ratings?"
</div>


## 🎯 Project Overview

This project examines the 'We Rate Dogs' Twitter account to determine what features of the tweets (e.g., Comedic or Aesthetic) drives engagement. To this end, I build multiple linear regression with only comedic features, then aesthetic features, then both and interpret the strength of each variable on engagement. It turns out that comedic features drive the most engagement, however this model only weeakly explains the variance in popularity meaning there is likely other unmeasured factors which contribute to engagement. 
## 📊 Dataset

The primary dataset for this analysis was sourced from the 'We Rate Dogs' Twitter account using the Twitter API. It contains detailed tweet data, including tweet text, user data, retweet count, favorite count, and other meta information. I also used a dataset with neural network classifications of each dog picture into its respective dog breed. 

## 🧹 Data Wrangling

The initial dataset from the Twitter API was in JSON format with , and several preprocessing steps were performed:
- **Beautiful Soup:** Extracted necessary fields from the raw JSON data and converted into a pandas DataFrame
- **Extensive Cleaning:** Cleaned dataframe with 13 different steps, removing any non-relevant meta information
- **Regex:** Parsed dog ratings, monikers, and names from the tweet text

## 🛠️ Feature Engineering

To improve the modeling phase, several new features were engineered in addition to the features already extracted from the tweet text. Also the target feature of `Popularity Rating` was created by summing retweets and favorites for each tweet.
- Text length of tweets as a new column
- Breeds were one-hot-encoded
- Time of day the tweet was posted
- **Target Variable:** Popularity Rating = retweets + favorites

## 📶 Exploratory Data Analysis (EDA)

EDA was performed to understand the underlying patterns in the data:
- Univariate Distribution of retweet count, favorite count, time of day, and neural net confidence level was explored
- Time series analysis was conducted to see engagement trends over time.

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/ed6f8d2a-f864-4873-a1cf-cb1f0285e7ae)

## 🖥️ Modeling

Three multiple linear regression models with different sets of features were trained to predict popularity rating. One MLR model had comedic features, another had aesthetic features, and the final had all features. Then the significance and effect size of each feature was assessed in each model. This graph highlights all the statistically significant variables in the all-features model.

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/1f472f5c-6a87-4297-a4ac-641376ddfac1)

## 📈 Discussion

From the analysis and modeling, several key insights were derived:
- **Comedic**: The comedic model was the most predictive model and tweets with higher dog ratings tend to get more retweets and favorites
- **Aesthetic**: No dog breed was statistically significant, however the nickname `doggo` and `puppo` had a positive impact on popularity. 
- **All Features**: Time passing (`date_number`) was a very important variable to have in the model as popularity Ratings rise dramatically over time as the account gets more fans and followers.

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/00a1a5f8-7b97-4417-9542-f67e1a660f92)


<div align="center">

Best Wishes, <br>
Sam Celarek

</div>

---

## 💡 Other Resources

- **[Link to the Jupyter Notebook](#)**
- **[Link to the full dataset](#)**
- **[Twitter API documentation](https://developer.twitter.com/en/docs)**

