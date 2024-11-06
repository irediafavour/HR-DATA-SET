# HR-DATA-SET
Documentation of the visualization of HR data
## Project topic: HR DATA SET
[Project Overview](#project-overview)

[Data Source](#data-source)

[Project Objectives](#project-objectives)

[Tools Used](#tools-used)

[Formula Used](#formula-used)

[DATA VISUALIZATION AND INFERENCE ](data-visualization-and-inference)

[CONCLUSION](conclusion)

### Project Overview
This project focuses on analyzing the provided HR dataset to understand employee demographics, job roles, job satisfaction, performance metrics, and attrition status. By examining these variables, the analysis aims to uncover patterns that contribute to employee turnover and retention.

### Data Source
1. Employee Demographics: Includes fields like age band, gender, education field, and marital status.
2. Job Details: Information on departments, job roles, and job levels, allowing for segmentation by role and seniority.
3. Performance Metrics: Performance rating.
4. Satisfaction Metrics: Job satisfaction ratings
5. Attrition Information: Identifies whether an employee is a current or former employee, allowing for comparisons between those who have left and those who are still with the company.

### Project Objectives
The primary objective is to identify factors contributing to employee attrition by analyzing the relationship between job satisfaction, demographics, and career progression. 

### Tools Used
Power BI for creating interactive visualizations and dashboards

### Formula Used
1. Attrition rate = sum ('HR data' [Attrition Count]) / sum ('HR data' [Employee Count])
2. Average age = AVERAGE ('HR data' [age])
3. Use of conditional columns

## DATA VISUALIZATION AND INFERENCE 
The HR Data Analysis Tracker dashboard provides a comprehensive overview of key employee metrics, enabling the identification of trends in attrition and the assessment of areas requiring improvement to enhance employee retention.

![HR visualization](https://github.com/user-attachments/assets/592f4f03-a060-48b2-950f-48413593d921)

- Total Number of Employees: Displays that there are **1,470 employees** in the organization

- Total Number of Attrition Count: Displays that **237 employees have left** the organization

- Total Current Number of Employees: Displays that the organization has **1,233 employees remaining** after counting for attrition

- Attrition Rate: Calculates the percentage of employees who have left the organization. 

- Average Age: This shows the average age of the employees.

- Attrition Count by Department: A pie chart that illustrates that the **Research and Development (R&D) department has experienced the HIGHEST number of departures with 133 employees leaving** while the **Human resource (HR) department has the LOWEST number of departures with 12 employees leaving**

- Attrition Count by Education Field: A bar chart that illustrates that **Life Sciences has the HIGHEST attrition count with 89 employees leaving** while the **Human resource (HR) department has the LOWEST with 7 employees leaving**

- Attrition Count by Gender: A pie chart that illustrates that more males left the department compared to females, having a ratio of **150:87**

This visualization focuses on analyzing attrition rates across different age groups and genders.

![Attrition](https://github.com/user-attachments/assets/246c87e9-10cb-4ce9-86a8-317dae175662)

- Under 25: This age group has an attrition count of **38**, with a slightly higher proportion of males leaving.

- 25-34: This age group has the **highest attrition count of 112**, with a higher proportion of males leaving.

- 35-44: This age group has an attrition count of **51**, with a higher proportion of males leaving.

- 45-54: This age group has an attrition count of **25**, with a higher proportion of males leaving.

- Over 55: This age group has the **lowest attrition count of 11**, with a higher proportion of males leaving.

This visualization shows a comprehensive overview of employee data, focusing on key metrics like job roles, gender distribution, marital status, education field, and satisfaction levels

![Employee](https://github.com/user-attachments/assets/64db2b9e-f589-4033-8b8c-d477560d4b56)

- Count of Current Employees by Gender and Age Band: This bar chart shows the number of current employees by age band, separated by gender (Male and Female) which highlights that the 35-44 age group has the **highest number of employees, with 272 males and 182 females** while Over 55 age bands, has the **lowest number of employees, with 36 males and 22 females**

- Job Role and Satisfaction Levels: This table displays employee satisfaction levels for different job roles, divided into categories: Dissatisfied, Satisfied, Very Dissatisfied, and Very Satisfied which indicates that **46 employees are Dissatisfied, 73 are Satisfied, 66 are Very Dissatisfied, and 52 are Very Satisfied.**

-  Marital Status by Gender: This table provides a breakdown of current employees by marital status and gender which shows that there are **(348) married males and married females (241), (198) single males and single females (152),  186 divorced male employees and 108 divorced female employees.** This shows that the organization has more married employees

- Satisfaction Levels by Education Field: This table categorizes employee satisfaction levels within different education fields which indicates that there are **46 employees who are Dissatisfied, 73 who are Satisfied, 66 who are Very Dissatisfied, and 52 who are Very Satisfied across all education fields.** Life Sciences and Medical have the highest number of employees, with varying satisfaction levels.

## CONCLUSION
This dashboard is a valuable tool for understanding and addressing the organization’s workforce dynamics. The key insights will enable the HR teams to make informed decisions to optimize workforce planning, boost employee satisfaction, enhance retention rates, and improve overall organizational performance.
