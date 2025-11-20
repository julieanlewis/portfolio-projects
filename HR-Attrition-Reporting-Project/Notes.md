# Notes on HR Attrition Analysis

This project is a simplified version of the HR attrition work I completed for DAT 430.
The steps below summarize how I prepared, cleaned, and explored the dataset.

1. Combined multiple HR data files and the training dataset into one dataset using Python and pandas, and used glob() to automatically load all matching HR files.
2. Renamed columns where needed so the data matched across files, then merged them into one complete dataset.
3. Checked for missing values, duplicates, and data type issues to make sure the combined dataset was clean and consistent.
4. Standardized categorical values and mapped BusinessTravel categories to numeric codes to support analysis.
5. Explored attrition patterns by Department, JobRole, JobSatisfaction, Gender, and other variables to see where turnover was highest.
6. Created visualizations (pie charts and bar charts) to show overall attrition and attrition by department and job role. These visuals helped identify key problem areas.
7. Calculated overall attrition rate and used it as a baseline to compare trends and support future modeling work.
