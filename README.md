# Bike_Purchase_report
## Table of contents 
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
### Introduction
In this analysis we seek to identify factors and reasons behind why people purchase bike to introduce and recommend strategies to improve bike sale.

![abiatm_dashboard](https://github.com/Abiatm/Bike-Sale_Report/assets/153201833/45f05ee0-0ff9-468a-86f7-272dd61c0bd1)


### Problem Statement
#### What we seek to identify are:
- Identification of the contributions of income by gender towards bike purchase .
- Effect of distance towards bike purchase.
- Age and house ownership contribution towards bike purchase

### Tools Used
- Excel- Data cleaning, wrangling and Exploration and Data visualization
- Power Bi- Data validation
- Dashboard Design- Data ink ratio

 ### Data Cleaning
 #### List of things checked and evaluated where necessary before performing data visualization
 
 - Removal of duplicates -here 26 cells with duplicate were removed
 - Find and Replacement of text -for readability purpose these was done on marital status, gender and Commute Distance column .
 - Data Type conversion-necessary columns of interest were considered
 - Formation of age bracket for different age groups using if statement
 - Data cleaning
 - Use of pivot table
 ### Data Analysis
```
Microsoft Excel-showing the first five lines of the cell code that was used to generated age bracket
(1)	= IF(L2>64,"Old_Age",IF(L2>39,"Middle_Adult","Early_Adult"))
(2)	= IF(L3>64,"Old_Age",IF(L3>39,"Middle_Adult","Early_Adult"))
(3)	= IF(L4>64,"Old_Age",IF(L4>39,"Middle_Adult","Early_Adult"))
(4)	= IF(L5>64,"Old_Age",IF(L5>39,"Middle_Adult","Early_Adult"))
(5)	= IF(L6>64,"Old_Age",IF(L6>39,"Middle_Adult","Early_Adult"))
```
### Results
The analysis results are summarized as follows:
1.	From the analysis it shows that the higher the income  from both gender the possibility of bikes purchase
2.	The smaller the distance the possibility of bike purchase.
3.	Middle age adult with age bracket of “40-64” has highest purchase of bike.
4.  Home owners has high chances of bike purchase.

### Recommendations
Based on the obtained results from the analysis, the following recommendations are made:
1.	Since income plays crucial role towards purchase of bike, I recommend more target on high-end bikes, customized options and improvement on premium services such as bike fitting and maintenance. .
2.	Sales staff are to be equipped with knowledge to effectively communicate with buyers on advantage and potentially resale value of the bikes.
3.	More focus should of advertisement and marketing should be on channels that middle age people likes the most . 
4.   Advertisement  should highlight the key health benefits of cycling and use of bikes for leisure rides.

