# HR Project Objectives
The analysis is incorporates the use two separate dashboard sheets titled "HR Summary" and the "HR Details". 
The objectives of the analysis are to 
- Provide summary-level views for high level insights related to employee demographics and income analysis.
- Develop a comprehensive and interactive tableau list that provides easy access to employee records information

Please click [here](https://public.tableau.com/views/HR_Dashboard_17343371058810/HRSummary?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) to access the interactive dashboards available on my Tableau public profile.

# About the datset <br>
The dataset was developed using ChatGPT as well as the Faker library for generating the data.

# HR Summary <br>
![Dashboard Screenshot](https://github.com/bayyangjie/Tableau-Projects/blob/main/HR%20Dashboard/HR%20Summary.png) <br>

The HR Summary dashboard is divided into three main categories namely Overview, Demographics and Income. More details about each section are explained below.

## Overview
The overview section focuses on providing a snapshot of the overall HR metrics.
- A total of 8950 employees were hired by the company and the number of terminated employees is at 966 while the active employees stands at 7984.
- The Operations Department has the highest number of hired as well as terminated employees. HR, Marketing and Finance departments have the lowest number of employee hired as well as terminated.
- Most of the employees are located in New York which is the company HQ. 6270 employees are located in the HQ while 2680 are in the branch office.
- Show the distribution of employees by city and state.

## Demographics
The Demographics section offers insights into the composition of the workforce, including:
- There are more male employees than females employees in the company but not by a large margin.
- Majority of employees hold a Bachelor's degree while PhD holders form the smallest population. Amongst employees who are Bachelor's degree holders, most are between the age of 35 to 44.
- Employees with higher education levels also tend to have higher performance ratings. Most high school education employees have the lowest performance rating while most PhD degree employees are given the highest performance rating.

## Income
The income analysis section shows how average salary levels vary between the correlation of variables such as Education, Gender and Age.

Education & Gender
- PhD degree holders have the highest average salary and females earn more than the males.
- Master degree holders have the second highest average salary with females also earning more than the males.
- For employees with only high school or bachelor degrees, males have higher average salary than the females.
- The salary gap between males and females is also the highest in employees with PhD degrees with an average difference of $13K.

Age & Salary
- The dotted horizontal and vertical lines demarcate the average age and annual salary of 41 years old and $78K respectively.
- Managers have above average salaries with Finance managers earning the most followed by IT and Sales managers. Managers in these job titles are also above the average age of 41.  
- HR managers have the lowest average salary as compared to other managerial positions while also above the average salary. On the other hand, they also belong to the younger age group of 32 which is below the average age of 41.
- Besides managerial positions, there are also employees in other non-managerial job titles such as Sales Consultant, Software Developer and Financial Analyst who are earning above the average salary.

# HR Details <br>
![Dashboard Screenshot](https://github.com/bayyangjie/Tableau-Projects/blob/main/HR%20Dashboard/HR%20Details.png) <br>

This dashboard provides a comprehensive list of all employees information such as name, department, position, gender, age, education, length of employment, employment status and salary. 

The dashboard is also developed in a way that enables users to be able to interact with the list through the use of filters located at the top of each column variable.

Colour codings and shapes:<br>

Demographics column
- Squares are used to represent males and circles for representing females

Geographics column
- Green represents locations in the state of New York, the HQ site. Grey represents the other office branches in the other non-HQ states.

Length of employment column
- Green represents employees that are hired and are still employed while purple represents employees that have been terminated.
