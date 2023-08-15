<div align="center">

<h1>Local vs Global Warming</h1>

<img src="https://github.com/scelarek/scelarek.github.io/assets/115444760/08653fda-f875-41b6-85b2-f7fd878b7f0e" title="Local vs Global Warming" alt="Local vs Global Warming" width="150" height="150">

<h2><strong>By Sam Celarek</strong></h2>

</div>

<div align="center" style="background-color: #CCCCD6; padding: 15px; border-radius: 10px;">
"How might we use descriptive statistics to compare the divergence of local city temperatures, such as Portland, from global temperature trends?"
</div>

## 🎯 Project Overview

In this project, I delve into historical temperature data to explore the relationship between global and local temperature patterns. A notable shift in global temperature trends around 1820 prompted an in-depth analysis of the period before and after this critical juncture.

## 📊 Dataset

The primary dataset consists of historical global and city average yearly temperature readings provided by Udacity's SQL server. After using SQL to query the database, I downloaded the data, and joined the global and city temperatures over the past 200 years on year.

## 📶 Exploratory Data Analysis (EDA)

The analysis began with visualizations of temperature trends over time. Significant climate events or anomalies were identified by observing spikes and trends in temperatures. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/5981defb-4174-4fd1-8c0b-9ed6624de9c6)

## 🖥️ Modeling

Next I used Linear Regression Line of Best Fit to better illustrate the central trend of temperatures over long periods of time. Here we can see that Portland's temperatures appear to be rising _faster_ than global temperatures. Global temperatures also appear to trend up much more strongly after 1820. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/a318bbae-0e11-45cd-8f12-e11efb377279)

When one separates the data into "pre-industrial" and "post-industrial" periods, there is very different global temperature trend lines, as revealed in the graph below. Although I did not use any time series models to further enhance this analysis, the linear regression line helps visualize the potential trajectory of global temperatures if current post-industrial patterns persist. 

![image](https://github.com/scelarek/scelarek.github.io/assets/115444760/ddb723ff-8c6c-4ad0-949e-b632a26966a1)


## 📈 Discussion

As we can see in the graphs above, global temperatures rising is a relatively recent phenomenon occuring approximately after industrialization in 1820. The consequences of this trend are vast, influencing sea levels, biodiversity, and more. Although we cannot use this simple model to accurately extrapolate temperature trends into the future, this analysis reinforces the importance of addressing climate change for policymakers and the public. 

<div align="center">

Best Wishes, <br>
Sam Celarek

</div>

---

## 💡 Other Resources

- **[Project Jupyter Notebook](#)**
- **[Original Dataset Source](#)**
- **[More on Global Warming](https://www.ipcc.ch/)**

