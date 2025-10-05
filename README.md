🌎 COVID-19 & Worldwide Happiness Data Analysis
📘 Overview

This project analyzes and compares COVID-19 data (daily confirmed cases, deaths, recoveries by country and date) with the Worldwide Happiness dataset (happiness scores and socioeconomic indicators such as GDP, social support, and health).

The goal is to uncover insights on how the COVID-19 pandemic may have influenced global happiness and well-being across countries and regions.

🎯 Objectives

Study global COVID-19 trends (cases, deaths, recoveries) over time.

Analyze worldwide happiness indicators and their relationships with economic and social factors.

Explore correlations between COVID-19 impact and happiness levels.

Identify countries and regions most affected in terms of well-being.

🧩 Datasets
1. COVID-19 Dataset

Source: [Our World in Data / WHO]

Attributes:

Country

Date

Confirmed Cases

Deaths

Recoveries

Vaccinations (if available)

2. Worldwide Happiness Dataset

Source: [World Happiness Report / Kaggle]

Attributes:

Country

Happiness Score

GDP per Capita

Social Support

Healthy Life Expectancy

Freedom to Make Life Choices

Generosity

Perceptions of Corruption

⚙️ Methodology
1. Data Cleaning and Preparation

Removed duplicates and missing values.

Standardized country names across datasets for merging.

Converted dates into consistent formats.

Aggregated COVID-19 daily data to compute total and average values per country.

2. Merging Datasets

Joined both datasets using the Country field.

Created a combined dataset linking COVID-19 impact indicators with happiness scores and other factors.

3. Exploratory Data Analysis (EDA)

Computed descriptive statistics (mean, median, correlations).

Visualized trends using Matplotlib, Seaborn, and Plotly.

Analyzed relationships between COVID-19 metrics and happiness indicators.

4. Visualization & Insights

Time-series graphs of COVID-19 confirmed cases and deaths.

Correlation heatmaps between happiness factors and pandemic statistics.

Scatter plots showing relationships (e.g., GDP vs Happiness Score, Death Rate vs Happiness).

Country-wise and continent-wise comparisons.

📊 Tools & Technologies

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly

Environment: Jupyter Notebook / Google Colab

🔍 Key Findings

Countries with higher GDP and stronger social support systems maintained higher happiness scores even during the pandemic.

Higher COVID-19 death rates showed a negative correlation with happiness levels.

Nations with effective vaccination drives and better healthcare experienced a faster recovery in happiness scores post-2021.

Economic and social stability played a major role in emotional well-being during the crisis.

📈 Conclusion

The analysis highlights that the COVID-19 pandemic had a significant but uneven impact on global happiness. Economic strength, healthcare quality, and social support emerged as key factors that helped countries sustain well-being during challenging times.
