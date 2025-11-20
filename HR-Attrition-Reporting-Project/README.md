# HR Attrition Analysis – Portfolio Summary

This project is a condensed version of my DAT 430 HR Attrition work, where I combined multiple HR datasets, cleaned and standardized the data, and explored key factors that contribute to employee attrition. The goal was to understand what influences employees to leave and what metrics can support better retention decisions.

## Project Purpose
The purpose of this analysis was to determine what drives employee attrition and to develop meaningful metrics based on employee demographics, job characteristics, satisfaction scores, and employment history.

## Data Preparation
To build a complete dataset:
- I used Python and pandas to load the training dataset and automatically import multiple HR files using the `glob` module.
- I renamed inconsistent columns to ensure alignment across files.
- I merged all datasets into one unified DataFrame.
- I checked the combined dataset for missing values, duplicates, and inconsistent data types.
- I standardized categorical fields to maintain consistency.
- I mapped the BusinessTravel categories from text values to numeric codes to support analysis.

## Exploratory Analysis
I explored attrition patterns across several factors, including:
- Department  
- JobRole  
- JobLevel  
- JobSatisfaction  
- Gender  
- Overtime  
- YearsAtCompany  

I also calculated the overall attrition rate to establish a baseline understanding of the workforce. Examining attrition by department and job role helped highlight areas with higher turnover and identify possible contributing factors.

## Visualizations
To support interpretation of the data, I created:
- A pie chart showing the overall attrition rate  
- Bar charts illustrating attrition by department and by job role  
- Additional visuals showing patterns in satisfaction, tenure, and overtime  

These visualizations made it easier to identify trends and understand the relationships within the data.

## Project Summary
This project demonstrates work in:
- Combining and preparing multiple datasets  
- Cleaning and organizing data using Python  
- Standardizing categorical fields for analysis  
- Conducting exploratory analysis  
- Creating clear, meaningful visualizations to communicate findings
