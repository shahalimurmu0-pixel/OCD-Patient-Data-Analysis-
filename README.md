# OCD-Patient-Insights (Interactive Dashboard using SQL & Power BI)

## Summary
This project is about turning raw OCD patient data into clear insights. Using SQL queries and Power BI, I built an interactive dashboard that shows how OCD symptoms vary across age groups, genders, education levels, and treatments. 

## Overview 
This project studies data from 1,500 OCD patients using SQL and Power BI. The dataset includes details like age, gender, education, family history, obsession and compulsion types, scores, and medications. SQL queries were used to answer 14 key questions, and the results were shown in Power BI with charts and filters. The dashboard makes it easy to see patterns such as which age group has the highest scores, which compulsions are most common, and how family history or medication affects symptom duration

## Problem Statement
Raw patient data is difficult to understand on its own. Tables with hundreds of rows don’t clearly show which age group has the highest OCD scores, which compulsions are most common, or how family history and medications affect symptom duration. This project solves that challenge by using SQL queries to extract answers and Power BI visuals to present them in a clear way. The dashboard makes complex clinical information easy to explore. 

## Dataset Used
- <a href="https://1drv.ms/x/c/05B39122E1F4EA1E/IQC77c2gNsUGSpeOsxWexxvTAeQEyEnClsRO4Pe71OhC7O4?e=FJb4iv">Dataset </a>

## Tools and Techniques Used
- Excel – used for cleaning the dataset (removing duplicates, fixing missing values)
- SQL (MySQL Workbench) – used for writing queries and extracting insights
- Power BI – used for creating charts and visuals (bar, line, clustered column, pie)
- Slicers in Power BI – added for easy filtering and interaction

  ## Questions (KPIs)
- Gender distribution of OCD patients
- Which ethnicity has the highest average compulsion score
- Which age group has the highest average OCD score
- Most common compulsion type among patients with depression and anxiety
- Medications linked with the longest average symptom duration
- Duration of symptoms by education level and gender
- Ethnic–gender groups with the highest compulsion scores
- Impact of marital status and education on symptom duration
- Obsession–compulsion pairs with the highest severity scores
- Previous diagnoses linked to highest OCD scores
- Effect of medication and marital status on symptom duration
- Family history impact on duration for males and females
- Obsession types with the highest OCD scores
- Most frequent compulsion types overall

  Dashboard interaction - <a href="https://github.com/shahalimurmu0-pixel/OCD-Patient-Data-Analysis-/blob/main/Screenshot%202025-12-08%20235142.png">View Dashboard </a>

## process
- Excel – first used to clean the raw dataset (remove duplicates, fix missing values, prepare columns).
- SQL (MySQL Workbench) – then imported the cleaned dataset and created tables. From there, you wrote 14 queries to answer the key questions.
- Power BI – finally used to connect with SQL outputs, build charts (bar, line, clustered column, pie), and add slicers for interactive filtering.
- Dashboard Design – applied layout, colors, and titles to make insights easy to read and visually appealing.

 ## Dashboard
 <img width="1307" height="736" alt="Screenshot 2025-12-08 235142" src="https://github.com/user-attachments/assets/05f91434-5e3f-4a0a-b5e9-e7637ead01ef" />


## Insights
- Male patients show slightly higher average OCD scores compared to females.
- Certain ethnic groups have higher compulsion scores than others.
- The age group 21–30 years records the highest average OCD scores.
- Depression and anxiety are strongly linked with specific compulsion types.
- Medications influence symptom duration, with some linked to longer persistence.
- Family history plays a clear role in symptom severity and duration.
- Education and marital status also affect how long symptoms last.

 ## Conclusion
This project demonstrates how clinical data can be transformed into meaningful insights using Excel, SQL, and Power BI. By cleaning the dataset, creating queries, and building an interactive dashboard, complex information about OCD patterns becomes clear and easy to interpret. The analysis highlights important factors such as age, gender, family history, and medication, providing a structured view that supports better understanding of patient outcomes.











