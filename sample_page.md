<div align="center">

# Eternal Growth, Immortal Inequality
<img src="https://github.com/scelarek/Eternal-Growth-Immortal-Inequality/blob/main/Data/Logo%20for%20Economics.png" title="Eternal Growth, Immortal Inequality" alt="Eternal Growth, Immortal Inequality" width="150" height="150"> 

## **By Sam Celarek**
</div>

## 🎯 Project Overview
<div align="center" style="background-color: #f5f5f5; padding: 15px; border-radius: 10px;">
</div>

By analyzing econometric data from Gapminder, this project aims to explore the relationship between a countries' wealth, inequality, and human flourishing. To do this I used bivariate data exploration and look at the trends of countries in each quintile over time. 

## 📊 Dataset
The data for this project comes primarily from **Gapminder**, which collects data from various sources worldwide, enabling a comprehensive understanding of global economic trends.  From Gapminder, I downloaded csv's on every nations' Real GDP, Gini Coefficient, Happiness, Murder Rate, Freedom Index (7 being the least free, 1 being the most free), and CO2 Emissions from up to 200 years ago. 

## 🧹 Data Wrangling
The six different data sets were joined on the year and country columns. There were many missing values which eventually led me to trimming the time span over which the relevant analysis covered. 

## 🛠️ Feature Engineering
To better explore the trends of countries that are the most rich versus the most poor, I created categories for each country based on which quintile they resided in on average over the past 200 years. For example, each country was assigned a 'GDP quintile' based on whether it had been amongst the 80-100th, 60-80th, 40-60th, etc... percentile of GDP for countries over the past 200 years. I then would aggregate each quintiles scores and look at the quintiles trends over time. 

## 📶 Exploratory Data Analysis (EDA)
The EDA phase involved scatter plots, line plots for each quintile, bar charts for each quintile, and correlation heatmaps between each of the econometric indicators. Here is a quick sample of the exploration of the relationship between GDP and the wellfare metrics of happiness, murder rate, and freedom (lower is better):

![image](https://github.com/scelarek/Eternal-Growth-Immortal-Inequality/assets/115444760/74cef867-0ff3-47fd-a34c-a2f886f28db8)
![image](https://github.com/scelarek/Eternal-Growth-Immortal-Inequality/assets/115444760/3df651dd-400b-4643-b965-d7eaf2c8730a)
![image](https://github.com/scelarek/Eternal-Growth-Immortal-Inequality/assets/115444760/da66e762-030e-4328-af54-118d543ecb74)

And here is a final correlation heatmap:

![image](https://github.com/scelarek/Eternal-Growth-Immortal-Inequality/assets/115444760/7b9e9130-2bfa-41ad-8a9a-9d51123e77df)


## 📈 Analysis
The project's findings were exploratory in nature as no tests of statistical significance were conducted. However there were four key correlations observations: 

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

## 💡 Other Resources

- **[Jupyter Notebook](/eternal_growth_immortal_inequality.ipynb)**
- **[PDF of Notebook](/Sam_Celarek_eternal_growth_immortal_inequality.pdf)**
- **[Data Source: Gapminder](https://www.gapminder.org)**

Thank you for your interest in **Eternal Growth, Immortal Inequality**. For any further inquiries or insights, please feel free to reach out through this GitHub repository or at scelarek@gmail.com.

<div align="center">

**Best Wishes,**  
*Sam Celarek*

</div>

---

