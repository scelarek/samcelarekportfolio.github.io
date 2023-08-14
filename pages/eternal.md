<div align="center">

<h1>Eternal Growth, Immortal Inequality</h1>


<h2><strong>By Sam Celarek</strong></h2>
</div>

<img src="https://github.com/scelarek/scelarek.github.io/blob/master/images/Logo%20for%20Economics.png" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality" width="150" height="150"> 

<div align="center" style="background-color: #CCCCD6; padding: 15px; border-radius: 10px;">
"How Does a Country's Wealth and Inequality Shape Human Flourishing?"
</div>

## 🎯 Project Overview

By analyzing econometric data from Gapminder, this project aims to explore the relationship between a countries' wealth, inequality, and human flourishing. To do this I used bivariate data exploration and look at the trends of countries in each quintile over time. 

## 📊 Dataset
The data for this project comes primarily from **Gapminder**, which collects data from various sources worldwide, enabling a comprehensive understanding of global economic trends.  From Gapminder, I downloaded csv's on every nations' Real GDP, Gini Coefficient, Happiness, Murder Rate, Freedom Index (7 being the least free, 1 being the most free), and CO2 Emissions from up to 200 years ago. 

## 🧹 Data Wrangling
The six different data sets were joined on the year and country columns. There were many missing values which eventually led me to trimming the time span over which the relevant analysis covered. 

## 🛠️ Feature Engineering
To better explore the trends of countries that are the most rich versus the most poor, I created categories for each country based on which quintile they resided in on average over the past 200 years. For example, each country was assigned a 'GDP quintile' based on whether it had been amongst the 80-100th, 60-80th, 40-60th, etc... percentile of GDP for countries over the past 200 years. I then would aggregate each quintiles scores and look at the quintiles trends over time. 

## 📶 Exploratory Data Analysis (EDA)
The EDA phase involved scatter plots, line plots for each quintile, bar charts for each quintile, and correlation heatmaps between each of the econometric indicators. Here is a quick sample of the exploration of the relationship between GDP and the wellfare metrics of happiness, murder rate, and freedom (lower is better):


<div align="center">
<img align="center" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/fd4a32e8-dc95-4ef7-8da4-7b4281c3ab07" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality" width="300" height="300">  
</div>

There appears to be a fairly robust correlation with increased GDP and increased happiness, although it is notable that above a GDP of $50,000 this correlation appears to weaken. It is also notable that many of the happiness scores lie above 30 and below 80. This seems to imply some type of subjective self-evaluation cutoffs that people often don't rate themselves beyond.  

<div align="center">
<img align="center" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/904306d0-6107-4433-ac77-fe3e84b58525" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality" width="300" height="300"> 
</div>

Here one can observe that the freedom index of countries in each quintile of GDP have remained fairly constant over time with the biggest increases in average freedom coming from the 0-20th and 60-80th quintiles. It also would appear that there has been some slight loss in average freedom since 2008 across all quintiles.

<div align="center">
<img align="center" src="https://github.com/scelarek/scelarek.github.io/assets/115444760/5c470243-9205-455b-ad6e-07b7f9f735db" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality" width="300" height="300"> 
</div>

This graph seems to strongly imply that more egalitarian countries are associated with a lower murder rate, however it is difficult to make this conclusion due to the lack of data from countries in the higher quintiles of inequality. 


<div align="center">

   <h3> Correlation Heatmap of All Metrics: </h3>
   <img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/2e53793e-25a1-4090-8961-0327a44671c6" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality"> 
</div>


The strongest correlation between individual countries econometrics is happiness and gdp with a r = 0.74. Other stand out metrics are a strong positive correlation of CO2 and GDP (r=0.7), a weak positive correlation between murder rate and inequality (r=0.42), and inverse correlation between freedom and happiness (r=-0.53).  


## 📈 Analysis
The project's findings were exploratory in nature as no tests of statistical significance were conducted. However there were four key correlations observations from the above visualizations and the analysis performed in the notebook beyond what is presented here: 

1. **The Welfare of Nations**:
   - There's a positive correlation between GDP per capita and happiness.
   - Richer countries generally have lower murder rates and more civic freedom.

2. **Rich Man, Poor World**:
   - A strong positive association exists between GDP per capita and CO2 emissions.
   - However, the richest countries have seen CO2 emissions decrease over the past 30 years, even as their GDP increased, suggesting a potential dissociation between the two.

3. **Progress and Poverty**:
   - There's an inverse correlation between GDP per capita and economic inequality (Gini coefficient). That is richer countries have less Gini-inequality. 

4. **The Gini's Curse**:
   - Economic inequality (Gini coefficient) weakly correlates with decreased happiness and freedom.
   - There's a moderate correlation between high inequality and increased murder rates, but this is based on sparse data.

Thank you for your interest in **Eternal Growth, Immortal Inequality**. For any further inquiries or insights, please feel free to reach out through this GitHub repository or at scelarek@gmail.com.

<div align="center">

Best Wishes, <br>
Sam Celarek

</div>

---

## 💡 Other Resources

- **[Jupyter Notebook](/eternal_growth_immortal_inequality.ipynb)**
- **[PDF of Notebook](/Sam_Celarek_eternal_growth_immortal_inequality.pdf)**
- **[Data Source: Gapminder](https://www.gapminder.org)**
