# Student-Count-Analysis-Dashboard

## Problem Statement
This dashboard helps in analyzing student well-being and academic performance factors. It provides insights into how variables such as sleep duration, study hours, study satisfaction, academic pressure, and financial stress correlate with student count. By visualizing these relationships, institutions can identify patterns that affect student health and learning outcomes, and take corrective measures to improve student support systems.

## Steps followed
 - Step 1 : Uploaded dataset as a flat file into MS SQL Server Management Studio (SSMS).

 - Step 2 : Performed data cleaning in SQL Server (handled nulls, standardized column names, removed duplicates).

 - Step 3 : Connected the cleaned dataset from SQL Server to Tableau Desktop.

 - Step 4 : Created calculated fields and measures to represent student count across different categories.

 - Step 5 : Designed multiple visualizations:

   - Sleep Duration vs Student Count

    - Study Hours vs Student Count

    - Study Satisfaction vs Student Count

    - Academic Pressure vs Student Count

    - Financial Stress vs Student Count

 - Step 6 : Added filters for dimensions such as Gender, Age Group, and Academic Year.

 - Step 7 : Inserted text boxes for project title and institutional tagline.

 - Step 8 : Styled the dashboard with a professional theme and published it to Tableau Server/Tableau Public.

## Snapshot of Dashboard (Tableau Desktop)
<img width="960" height="489" alt="Image" src="https://github.com/user-attachments/assets/1918b3dd-9dd9-4624-b0f9-8c1855539ae6" />

# Insights
A single-page dashboard was created in Tableau Desktop and published for sharing.

Following inferences can be drawn from the dashboard:

## [1] Sleep Duration & Student Count
5–6 hours → 18 students

7–8 hours → 12 students

Less than 5 hours → 11 students

More than 8 hours → 5 students  
 Most students sleep between 5–6 hours, indicating possible sleep deprivation.

## [2] Study Hours & Student Count
Student count varies across 12 study hour intervals, with peaks at 53 students and 46 students.
 Higher study hours correlate with increased student participation.

## [3] Study Satisfaction & Student Count
Satisfaction Level 3 → 12 students

Satisfaction Level 4 → 13 students  
 Majority of students fall in the mid-range satisfaction levels, suggesting room for improvement.

## [4] Academic Pressure & Student Count
Pressure Level 5 → 13 students

Pressure Levels 1 & 3 → 9 students each  
 A significant number of students report high academic pressure.

## [5] Financial Stress & Student Count
Stress Level 3 → 13 students

Stress Levels 1 & 5 → 10 students each  
 Financial stress is a moderate to high concern among students.
