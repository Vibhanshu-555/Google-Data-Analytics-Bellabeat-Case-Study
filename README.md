# Bellabeat Case Study – Fitbit Wellness Data Analysis

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-009688?style=flat&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/)

---

## Executive Summary
This project analyzes **Fitbit Fitness Tracker data** to uncover patterns in users’ daily activity, sleep, and wellness behaviors.  
The analysis helps **Bellabeat**, a smart wellness company for women, derive **data-driven insights** to enhance engagement and product relevance.  
Using **Python for exploration, cleaning, and visualization**, the study translates behavioral trends into **actionable business recommendations** for Bellabeat’s product line: *Leaf*, *Time*, *Spring*, and *Membership*.

**Dataset**  
[**FitBit Fitness Tracker Data**](https://www.kaggle.com/datasets/arashnic/fitbit/data)

**Reports & Files:**  
- [Jupyter Notebook (.ipynb)](./notebook/Bellabeat_Case_Study_03_NOV.ipynb)  
- [Share Phase Report (Markdown)](./report/Bellabeat_report.md)
- [Share Phase Report (Presentation)](./report/Bellabeat_Presentation.pptx)
---

## Business Problem
Bellabeat aims to empower women with data-driven wellness insights.  
To scale effectively, it needs to understand **how users engage with fitness trackers** — their activity levels, sleep quality, and consistency — and use those insights to design **targeted marketing and product improvements**.

---

## Methodology
- **Data Exploration (EDA):** Inspected columns, nulls, and distributions  
- **Data Cleaning:** Removed duplicates, formatted dates, merged datasets  
- **Feature Engineering:** Created Day-of-Week, BMI categories, and correlations  
- **Visualization:** Analyzed activity, sleep, and calories through histograms, bar charts, and heatmaps  
- **Insight Synthesis:** Summarized findings into clear, story-driven insights  

---

## Skills & Tools
- **Python:** `pandas`, `numpy`, `matplotlib`, `seaborn` – data cleaning & visualization  
- **Environment:** Jupyter Notebook in VS Code  
- **Analytics Skills:** Data wrangling, pattern recognition, storytelling, and actionable insights  

---

## Key Insights
- Users spend **over 80% of the day sedentary**, signaling low overall movement.  
- **Activity peaks on Saturday, Tuesday, and Monday**, dropping midweek.  
- **Steps and calories** show a **moderate positive correlation (r = 0.59)**.  
- **Sleep and steps** have a **weak negative correlation (r = –0.19)**, suggesting trade-offs between movement and rest.  
- **BMI average: 25.2**, with most users in the **normal-to-overweight range**.  

![Activity Distribution](Bellabeat_charts/activity_distribution.png)
![Steps vs Calories](Bellabeat_charts/step_vs_calories.png)
![Correlation Heatmap](Bellabeat_charts/health_correlation.png)

---

## Business Recommendations
Fitbit data reveals users’ ongoing pursuit of balance — active yet inconsistent, motivated yet often sedentary.  
Bellabeat can leverage these insights to design **empathetic, data-informed wellness experiences**:

- **Promote Consistent Activity:**  
  Encourage small, everyday goals via *Leaf* and *Time* trackers.  
- **Enhance Sleep Wellness:**  
  Use *Time* watch reminders for bedtime and relaxation prompts.  
- **Boost Hydration Awareness:**  
  Integrate *Spring* smart bottle insights into the Bellabeat app.  
- **Combat Sedentary Patterns:**  
  Introduce mindful movement notifications in the Bellabeat App.  
- **Personalized Wellness:**  
  Offer *Membership*-based analytics and holistic lifestyle guidance.  

---

## Next Steps  
To elevate business impact and analytic maturity, Bellabeat can advance from **descriptive** to **predictive and prescriptive** insights:

- **Expand Data:** Add demographics, nutrition, and cycle data for deeper segmentation.  
- **Time Series Trends:** Track activity and sleep over time to detect behavior shifts.  
- **Predictive Models:** Forecast daily steps or calorie burn with machine learning.  
- **User Clustering:** Group users by lifestyle (active, balanced, sedentary) for targeted marketing.  
- **Engagement Tracking:** Link app usage to wellness outcomes to improve features.  
- **Dynamic Dashboards:** Build Power BI or Tableau dashboards for real-time insights.  
