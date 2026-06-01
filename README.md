## Student Depression Analysis and Student Well-Being Dashboard | SQL & Tableau


## Project Overview

Student Depression Analysis and Student Well-Being Dashboard is a data analysis project developed using SQL Server and Tableau to study factors related to student mental health and depression. The project focuses on understanding how academic pressure, financial stress, study satisfaction, sleep duration, and study hours influence student well-being.
The dataset was first imported and prepared in SQL Server, where data cleaning, column modifications, and exploratory analysis were performed. The processed data was then connected to Tableau to create individual visualizations and an interactive dashboard for student count analysis. The dashboard helps identify patterns and provides insights into factors associated with student depression and overall well-being.


## Problem Statement

Student mental health and depression are influenced by multiple academic and personal factors, making it difficult to identify patterns through raw data alone. Educational and mental well-being studies require structured analysis to understand how factors such as academic pressure, financial stress, study satisfaction, sleep duration, and study hours relate to student depression. This project aims to analyze these factors using SQL and Tableau to create meaningful visual insights and support better understanding of student well-being


## Dataset Information

The project uses a Student Depression Dataset containing information related to student demographics, academic conditions, lifestyle habits, and mental well-being factors. The dataset includes variables such as Gender, Age, Academic Pressure, Financial Stress, Study Satisfaction, Sleep Duration, Study Hours, Dietary Habits, Family History of Mental Illness, Suicidal Thoughts, and Depression status. The dataset was imported into SQL Server for data preparation and exploratory analysis before being connected to Tableau for visualization and dashboard development


## Tools & Technologies Used

-SQL Server – Used for data import, cleaning, column modification, and exploratory analysis.

-Tableau Desktop – Used for creating visualizations and developing the Student Count Analysis Dashboard.

-SQL Queries – Used for data transformation, grouping, and distribution analysis.
-Data Cleaning & Preparation – Used to standardize and prepare data for visualization and analysis

## Steps Followed

-Imported the Student Depression dataset into SQL Server.
-Performed data cleaning and preprocessing by modifying Gender values and checking null/blank records.
-Created the Age_Group column using SQL CASE statements for age segmentation.
-Added an Index_Column for structured record identification.
-Updated and standardized the Depression column values from numeric to categorical format (Yes/No).
-Conducted SQL exploratory analysis using GROUP BY and distribution queries across multiple factors.
-Connected the prepared SQL Server dataset to Tableau Desktop.
-Built individual visualizations for Academic Pressure, Financial Stress, Study Satisfaction, Sleep Duration, and Study Hours.
-Combined the visualizations into a Student Count Analysis Dashboard to generate insights into student well-being and depression-related factors.


## SQL Data Import & Preparation

-Created the Tableau Project 1 database in SQL Server.
-Imported the Student Depression Dataset into SQL Server.
-Modified the Gender column to standardize values (Female → F, male → M).
-Checked for null and blank values to ensure data consistency.
-Created the Age_Group column using SQL CASE statements to categorize students by age.
-Added an Index_Column using IDENTITY(1,1) for record indexing.
-Modified and updated the Depression column by converting numeric values into categorical values (Yes / No) for better readability and analysis.


## SQL Exploratory Analysis

This section explains the analysis performed using SQL queries before moving to Tableau visualization.

-Performed Gender distribution analysis using GROUP BY queries.
-Analyzed Age and Age_Group distribution to understand student segmentation.
-Conducted Academic Pressure distribution analysis using student counts.
-Examined Study Satisfaction distribution using grouped SQL queries.
-Analyzed Sleep Duration distribution and student count patterns.
-Evaluated Dietary Habits distribution among students.
-Studied Suicidal Thoughts distribution using grouped analysis.
-Performed Study Hours distribution analysis to observe study patterns.
-Examined Financial Stress distribution using student counts.
-Analyzed Family History of Mental Illness distribution.
-Evaluated Depression status distribution after data standardization.
-Used SQL GROUP BY and aggregation queries to study frequency and count patterns across multiple student well-being factors

## Dashboard Snapshot start from here###############

![Student Depression Dashboard](https://github.com/user-attachments/assets/f674d7fe-7443-4fd7-ae9b-e85008a5e23c)

## Key Insights

- Students experiencing higher academic pressure show higher levels of depression.
- Lower sleep duration is associated with increased depression rates.
- Financial stress significantly impacts student mental health.
- Students with lower study satisfaction tend to report higher depression levels.
- Certain age groups show higher vulnerability to depression.
- Interactive dashboard helps identify mental health trends quickly and effectively.

- ## Tools Used

- SQL Server (Data Cleaning & Analysis)
- Tableau (Data Visualization & Dashboard Creation)

- ## Project Summary

Analyzed 503 student records using SQL and Tableau to identify factors influencing student depression. Performed data cleaning, transformation, and aggregation using SQL. Developed an interactive Tableau dashboard to visualize academic pressure, sleep duration, financial stress, study satisfaction, and depression trends. Generated actionable insights to understand the relationship between mental health and student lifestyle factors.
