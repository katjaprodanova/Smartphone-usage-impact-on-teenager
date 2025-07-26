# Teenager Smartphone Usage Analysis: Impact on Well-being and Academic Performance

## Project Overview

This project explores the relationship between smartphone usage patterns among teenagers (aged 13-19) and their impact on various aspects of their lives, including **academic performance, mental well-being (anxiety, depression, self-esteem,sleep), and potential addiction levels**. This analysis aims to uncover key trends, correlations, and risk factors associated with digital device engagement.

---

## Methodology

The analysis followed a structured approach to ensure data quality and derive meaningful insights:

* **Data Collection & Cleaning:** Initial dataset collection from Kaggle. Inspection and observing of the dataset for missing values (none, in this dataset), ensuring data integrity. I used the Pandas library for this step**.
* **Feature Engineering:** Four new columns were engineered to enrich the dataset's analytical depth. These included:
    * `SM_to_Edu_Ratio`: The ratio of time spent on social media to educational apps.
    * `Meets_Exercise_Guideline`: A boolean flag indicating adherence to recommended exercise hours.
    * `Addiction_Category`: Categorization of addiction levels (e.g., Low, Moderate, High).
    * `High_Addiction_Risk`: A boolean flag indicating a high risk of smartphone addiction.
* **Exploratory Data Analysis (EDA)** 
* **Simple visualization in Notebook** using the libraries Matplotlib and Seaborn
* **Exporting the new dataset, ready for Tableau** 
* **Advanced visualizations using Tableau** - Deeper insights and interactive visualizations were developed using **Tableau**, allowing for the exploration of complex relationships and patterns.

---

## Key Insights & Visualizations

The analysis yielded several significant findings, presented through a series of key visualizations:

### 1. Gender's Influence on Screen Time Ratio & Academic Performance

This scatter plot with trend lines reveals the **Simpson's Paradox**. While an overall linear trend might suggest a general relationship, a deeper examination by gender shows contrasting impacts.
For **females**, a higher `SM_to_Edu_Ratio` surprisingly correlates with **improved academic performance**, whereas for **males**, it is associated with **declining academic performance**. 

![Gender Influence](visualizations/Gender%27s%20Influence%20on%20Screen%20Time%20Ratio%20%26%20Academic%20Performance.png)

### 2. Average Daily Smartphone Usage by Age Group and Gender

This bar chart illustrates how `Daily_Usage_Hours` vary across different `Age` groups and between `Genders`

![Average Daily Smartphone Usage](visualizations/Average%20Daily%20Smartphone%20Usage%20by%20Age%20and%20Gender.png)

### 3. High Smartphone Addiction Risk by School Grade and Gender

This heatmap quickly identifies which groups of teenagers are at a higher risk of smartphone addiction. We break this down by their school grade and gender. The darker the color in a cell, the higher the percentage of teenagers in that specific group who are at a high addiction risk.

![High Smartphone Addiction Risk](visualizations/High%20Smartphone%20Addiction%20Risk%20by%20School%20Grade%20and%20Gender.png)


### 4. Primary Phone Usage Purpose Breakdown

This is a pie chart. We quickly can see here, for which purpose do the teenagers use their smartphone the most. In our case, there is not a huge difference between each of them.

![Primary Phone Usage Purpose Breakdown](visualizations/Primary%20Phone%20Usage%20Purpose%20Breakdown.png)

### 5. Anxiety level amongst different addiction categories

This is a collection of 3 gauge charts. The Gauge chart is not pre-included in the Tableau, I custom made it following an online tutorial and making different Calculated fields, manipulating with the colors to achieve 'transparency', and adding two pie charts - one in the another, to achieve this effect.

Each Gauge chart, represents a different 'Addiction category' - High, Moderate and Low. The 'fill' in the gauge charts represents the 'Anxiety level'. 
As we can see, the two variablees are *strongly positive* correlated. The higher the addiction category, the higher the anxiety level.

![Anxiety Level Amongst Different Addiction Categories](visualizations/Anxiety%20level%20amongst%20different%20addiction%20categories.png)

### 6. Daily Usage vs. Sleep Hours

Another scatter plot. Suprisingly, sleep hours are strongly positively corelated to the usage hours of the smartphone.

![Daily Usage vs. Sleep Hours](visualizations/Daily%20Usage%20vs.%20Sleep%20Hours.png)


### 7. Addiction Level vs. Academic Performance

Another scatter plot. Comparing the Genders, and their addiction level influence on the academic performance. Similar to the Visualization n.1, we can see the very similar trend happening over here. The Male's academic performance goes down, the more addiction level they have, and suprisingly, the Female's performance goes up, as their addiction level goes up.

![Addiction Level vs. Academic Performance](visualizations/Addiction%20Level%20vs.%20Academic%20Performance.png)


---

## Interactive Dashboard (Tableau Public)

[**Link to my Tableau Public Dashboard**](https://public.tableau.com/app/profile/katja.prodanova/viz/SmartphoneUsageandAddictionImpactinTeenagers/GendersInfluenceonScreenTimeRatioAcademicPerformance)

---

## Tools & Technologies

* **Programming Languages:** Python Notebook
* **Data Analysis Tools:** Excel, Pandas
* **Data Visualization:** Tableau and Matplotlib, Seaborn in Notebook, for inline vizualizations
* **Version Control:** Git & GitHub

---

## Contact

Feel free to connect with me for questions or collaboration.
