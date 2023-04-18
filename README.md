## Purpose: 

The purpose of this project is to perform data cleaning and analysis on HR data and creating a dashboard for visualization purpose.

## Tools Used :

- Data Cleaning & Analysis - MYSQL
- Data Visualization - Microsoft Power BI

## Data:

-  HR Data with over 22000 rows from the year 2000 to 2020.

## HR Dashboard

![](images/hr_dashboard.png)

## DATA CLEANING

***1. Rename the ID column***

![](images/code_id_rename_col.png)

***Result:***

![](images/id_col_change.png)

***2. Convert the birthdate column to Date from Text and format the date to %Y-%m-%d.***

![](images/code_birthdate_.png)

***Result:***

![](images/birthdate_date_format.png)

***3. Modify birthdate column datatype to DATE from Text***

![](images/birthdate_modify_col.png)

***4. Convert the hire_date column to Date from Text and format the date to %Y-%m-%d***

![](images/code_hiredate_date_format.png)
![](images/code_hiredate_modifycol.png)

***Result:***

![](images/hiredate_date_format.png)

***5. Convert the termdate column to Date from Text and format the date to %Y-%m-%d***

![](images/code_termdate_dateformat.png)

***Result:***

![](images/termdate_dateformat.png)

***6. Add an Age column to the table and populate the values based on birthdate***

![](images/code_age_col.png)

***Result:***

![](images/age_col.png)

## DATA ANALYSIS

***1. What is the gender breakdown of employees in the company?***

![](images/gender_breakdown.png)


***2.What is the race/ethnicity breakdown of employees in the company?

![](images/race_breakdown.png)


***3. What is the age distribution of employees in the company?***

![](images/age_group_count.png)


***4. How many employees work at headquarters vs remote locations?

![](images/headquarter_vs_remote.png)


***5. What is the average length of employment for employees who have been terminated?

![](images/avg_lenth_employment.png)


***6. How does the gender distribution vary across departments and job titles?

![](images/department_gender_6.png)


***7. What is the distribution of job titles across company?

![](images/jobtitle_dist_7.png)


***8. Which department has the highest attrition rate?

![](images/attrition_rate_8.png)


***9. What is the distribution of employees across locations by state?

![](images/location_count_9.png)


***10. How has the employee count changed over time based on hire and term date?***

![](images/net_change_percent_10.png)


***11. What is the tenure distribution for each department?

![](images/department_11.png)









