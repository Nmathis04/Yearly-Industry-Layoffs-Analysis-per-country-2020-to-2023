# Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023

## Business Task

#### Analyze data from 2020 through 2023 and determine how the Covid-19 pandemic affected employment trends and identify which industries were the most impacted.
#### This was a raw dataset that was used to demonstrate the ability to clean data and do an exploratory analysis using SQL. 

---

## Dataset Overview

- Name: [Global Layoff Data](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/main/layoffs.csv)

 
&emsp;AlexTheAnalyst (Mar 20, 2022). Excel Project Dataset. Github. https://github.com/AlexTheAnalyst/Excel-Tutorial/commits/main/Excel%20Project%20Dataset.xlsx
  
- Key Fields: company, location, industry, total laid off, percent laid off, date, funding stage, country, funds raised.
 ![image alt](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/9674da926e6f21edf53dc1ead464b2d503634ba9/layoff%20data%20snippet.png)
  
---

## Core Business Objectives
- Identify which industries had the greatest impact
- Identify geographic hotspots
- Support workforce planning
- Assess investment risk

--- 


## Cleaning Data

Using the MySQL application, I uploaded the CSV dataset and cleaned the dataset using SQL.
The steps that were taken to clean the data set were: 
1. Removing duplicates
2. Standardizing Data
3. Removing Nulls or Replacing Nulls with accurate information 
![image alt](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/bb97365a644b82052aaff40be20d970f52d59722/removing%20dups%201.png)

---

## Analyzing Data

I conducted an exploratory analysis of this dataset using SQL and Excel to create visuals. After cleaning the data I created pivot tables of the information from certain columns to create charts.  Displayed are the top ten companies, industries and countries that faced laying off the most employees between 2020-2023. Following is a display of the total laid off throughout the beginning and middled of each year. Lastly, the chart at the bottom shows the total laid off and the funds raised (millions).

| Top Ten Industries | Top Ten Companies   |
| ------------- | ------------- |
| ![Alt Text 1](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/7648368469b4d75c7c47d01549ce6eacf5caa0a2/Top%2010%20Industries.png) | ![Alt Text 2](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/7648368469b4d75c7c47d01549ce6eacf5caa0a2/Top%2010%20companies.png) |

| Top Ten Countries | Total Laid off   |
| ------------- | ------------- |
| ![Alt Text 1](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/7648368469b4d75c7c47d01549ce6eacf5caa0a2/Top%2010%20countries.png) | ![Alt Text 2](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/7648368469b4d75c7c47d01549ce6eacf5caa0a2/Total%20Laid%20Off.png) |

| Funds Raised & total laid off  | 
| ------------- |
![Alt image](https://github.com/Nmathis04/Yearly-Industry-Layoffs-Analysis-per-country-2020-to-2023/blob/2cb995139bdd4284901a83fbbe51d933375b87c0/Funds%20raised%20vs%20total%20laid%20off.png)

---

## Recommendations

All the previous steps taken helped me to see things that could be recommended for the companies impacted. Even with the correlation that this data is during the period of the pandemic era, there are steps that can be suggested to help strengthen the industries reviewed. With the United States having the most total laid off (even though the data contained a great amount of American based companies) the concentration is very notable when seeing that India didn't even have a 4th of the amount of the United States. I would recommend that companies work toward diversifying not just the location in which the business and its many store fronts resides but diversifying the workforce departments within their companies such as operations, suppliers, manufacturing, customer markets to prevent a significant layoff due to an economic crisis. 
