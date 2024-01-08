
# HR Analytics :Attrition Report

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

This dashboard helps the shows important info about employees attrition. It helps us see things like who might leave, how satisfied people are with their jobs, and other key details. The colorful charts make it easy to understand.
It shows the number of employees currently working in the oragnisation and the number of employees who left the company.
This dashboard give insight about the rate of attrition in different departmanent and attrition in different age group etc.



### Steps followed 
#### Data transformation
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : All the null values and errors then been removed.
- Step 4 : Deleted all unnecessary columns from the dataset for easy analysis.
- Step 6 : Added some columns and measure to increase understanding.
- Step 7 : After some cleaning the data set is loaded for visualization.

#### Data visualization
- Step 8 :Now visuals are added to the report. 
- Step 9 :Slicers were added to the filter the reoprt on the basis of some creteria.
##### Slicer 1- Marital Status
`Single` 
`Marrried`
`Divorced`

![Slicer1](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/1.png?raw=true)

##### Slicer 2- Over time
`Yes` `No`

![Slicer2](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/2.png?raw=true)

##### Slicer 3 -Job role
![Slicer3](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/3.png?raw=true)

`Healthcare Representative`

`Human Resources`

`Laboratory Technician`

`Manager`

`Manufacturing Director`

`Research Director`

`Research Scientist`

`Sales Executive`

`Sales Representative`

##### Slicer 4 - Gender
![Slicer4](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/4.png?raw=true)
`Male`
`Female`

 Step 10- Some cards were added to indicate the key performance 
  ###### Card 1- Total employees
  `Shows the total number of employees`

![card](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/5.png?raw=true)

  ###### Card 2-  Active employees
  `Shows the number of employees working in company right now`
  ![card](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/6.png?raw=true)

  ###### Card 3- Attrition
  `Shows the number of employees who left the company`
 ![card](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/7.png?raw=true)

 Step 11: Added a pie chart visual which shows attrition number and percentage of attrition in different departmanent of the company.
![charts](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/8.png?raw=true)

Step 12: Added a Column chart to number of Attrition in differnt age group.

`Age data in dataset was very clustered so ,I grouped the age column using power bi 'new group' feature.`
![charts](https://github.com/mukuldiwakar/Attrition-insights/blob/main/I/Images/9.png?raw=true)



          
