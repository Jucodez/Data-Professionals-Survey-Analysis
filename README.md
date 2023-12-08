# Data Professionals Survey Analysis


## Problem Statement

The survey to be examined gathered information on data professionals across different countries, with the goal of gaining insights into the current attributes of individuals working in the data industry.

Develop a dashboard to assist users in comprehending the collected data and gaining insights into the realities of being a data professional in their specific country.


## Steps followed 

- Step 1 : Load data from Microsoft Excel into Microsoft Power BI, transform data in power query.
- Step 2 : Remove unnecessary columns (Browser, OS, City, Country, Referrer).
- Step 3 : Split column "Q1 - Which Title Best Fits your Current Role?" by delimiter "(".
- Step 4 : Remove column"Q1 - Which Title Best Fits your Current Role?.2" created by splitting original column by delimiter "(".
- Step 5 : Split column "Q5 - Favorite Programming Language" by delimiter ":".
- Step 6 : Remove column"Q5 - Favorite Programming Language.2" created by splitting original column by delimiter ":".
- Step 7 : Split column "Q3 - Current Yearly Salary (in USD)" by character transition (Digit to Non-Digit). 
- Step 8 : Split column "Q3 - Current Yearly Salary (in USD).2" by character transition (Non-Digit to Digit)
- Step 9 : Remove unwanted columns "Q3 - Current Yearly Salary (in USD).2.1" and "Q3 - Current Yearly Salary (in USD).3"
- Step 10 : Replace null values in column "Q3 - Current Yearly Salary (in USD).2.2" with 225 
- Step 11 : Change data type of columns "Q3 - Current Yearly Salary (in USD).1" and "Q3 - Current Yearly Salary (in USD).2.2" to whole number
- Step 12 : Add custom column to calculate average of "Q3 - Current Yearly Salary (in USD).1" and "Q3 - Current Yearly Salary (in USD).2.2" 
- Step 13 : Remove unnecessary columns "Q3 - Current Yearly Salary (in USD).1" and "Q3 - Current Yearly Salary (in USD).2.2" 
- Step 14 :  Split column "Q4 - What Industry do you work in?" by delimiter " ".
- Step 15 :  Remove column"Q4 - What Industry do you work in?.2" created by splitting original column by delimiter " ".
- Step 16 :  Split column "Q11 - Which Country do you live in?" by delimiter "(".
- Step 17 :  Remove column "Q11 - Which Country do you live in?.2" created by splitting original column by delimiter "(".
- Step 18 :  Visualize country data with treemap to aid with dashboard filtering.
- Step 19 :  Visualize the average salary by job title using stacked bar chart
- Step 20 :  Visualize preferred programming language with stacked column chart
- Step 21 :  Visualize difficulty of entry into data with donut chart
- Step 22 :  Visualize number of respondents and average age of respondents with card visuals
- Step 23 :  Visualize average work life balance and salary satisfaction with Guage visuals.
- Step 24 :  Arrange visuals into cohesive dashboard.


## Insights

Screenshot of dashboard created

![Survey Dashboard](https://github.com/Jucodez/PowerBI/assets/102746691/c9962014-14d8-4a8b-b2ad-75700c93355d)

The following inferences can be drawn from the dashboard;

### [1] Preferred Programming Language 

   The most preferred programming lanuguage for data professionals according to the survey is python with R being a close second.
           
### [2] Average salary by Job Title

   According to the survey Data scientists have the highest salary among data professionals ($94k), with data engineers and data architect being second and third respectively ($65k and $64k)
 
### [3] Difficulty of Entry Into Data

   According to the survey, 42.7% of data professionals found it neither easy nor difficult to enter into the data field, while 24.76% found it difficult and found 21.27% it easy.

### [4] Average work life balance 

   According to the survey, the average work life balance of data professionals is 5.74 out of 10.

### [5] Average salary satisfaction

   According to the survey, the average salary satisfaction of data professionals is 4.27 out of 10.
