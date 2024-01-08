# HR Analytics: Attrition Report

## Introduction

This Power BI report is helping us understand and tackle employee attrition in hte organization. It looks into important details like why some might leave, how satisfied people are with their jobs, and other key insights. The colorful charts make it easy to understand the data.

### Dashboard Link
[Check out the Attrition Report Dashboard](https://app.powerbi.com/links/zJ0lwaAeVs?ctid=0496dd89-b3a0-41bb-a4f2-bf7a03d66176&pbi_source=linkShare)

## Problem Statement

This dashboard gives us insights of employee attrition, helping us identify who might leave and how satisfied people are with their jobs. The charts show the number of employees working now, those who left, and attrition rates in different departments and age groups.

### Steps Followed

#### Data Transformation

1. **Load Data:** Inport the data to Power BI Desktop from a CSV file.
2. **Power Query Editor:** Used Power query view option to check data quality and remove any errors.
3. **Data Cleaning:** Get rid of any missing values or mistakes from the dataset.
4. **Column deletion:** Remove unnecessary columns for easier analysis.
5. **Column Addition:** Add new columns for better understanding.
6. **Data Loading:** Load the cleaned dataset for visualization.

#### Data Visualization

7. **Visual Elements:** Time to add visuals to the report for a clearer presentation.
8. **Slicers:** Added slicers to report  based on criteria like Marital Status, Overtime, Job Role, and Gender.

   ##### Slicer 1 - Marital Status
   - `Single`
   - `Married`
   - `Divorced`

   ![Slicer1](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/1.png?raw=true)

   ##### Slicer 2 - Over Time
   - `Yes`
   - `No`

   ![Slicer2](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/2.png?raw=true)

   ##### Slicer 3 - Job Role
   - `Healthcare Representative`
   - `Human Resources`
   - `Laboratory Technician`
   - `Manager`
   - `Manufacturing Director`
   - `Research Director`
   - `Research Scientist`
   - `Sales Executive`
   - `Sales Representative`

   ![Slicer3](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/3.png?raw=true)

   ##### Slicer 4 - Gender
   - `Male`
   - `Female`

   ![Slicer4](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/4.png?raw=true)

9. **Key Performance Cards:** Add cards showing essential metrics.

   - **Card 1 - Total Employees:** Shows the total number of employees.
     
   ![Cards](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/5.png?raw=true)


   - **Card 2 - Active Employees:** Indicates how many employees are working now.
     
   ![Cards](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/6.png?raw=true)

   - **Card 3 - Attrition:** Displays the number of employees who left.
     
   ![Cards](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/7.png?raw=true)


   
10. **Pie Chart:** Shows attrition numbers and percentages across different departments.

    ![Pie Chart](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/8.png?raw=true)

11. **Column Chart:** Shows attrition in different age groups.

    ![Column Chart](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/9.png?raw=true)

12. **Matrix Table** Shows the job satisfaction rating and attrition count of different job role.
    
![Matrix Table](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/10.png?raw=true)
