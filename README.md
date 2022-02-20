# Module_07_Challenge
Module 07 Challenge - Pewlett-Hackard Employee Database

## Overview of Project
This project involves using PostgreSQL 11 to create a relational database from CSV files containing information about the workforce at Pewlett-Hackard, and then writing SQL statements to answer questions about and provide insight into the potential labor challenges the company may face as employees reach the age at which they may begin to retire. 

### Purpose
The purpose of this challenge is to take CSV files containing data related to the Pewlett-Hackard workforce, create a SQL database incorporating that data, execute SQL queries that will provide visibility into the number of employees approaching retirement age and their current titles, the number of employees by title who are approaching retirement age, and a listing of other experienced employees who may be well-suited to mentor less experienced employees as the company looks to fill vacancies which may result from the retirement of current employees.  

## Results
The resutls of our analysis of the data is as follows:

### Total Active Employee Headcount

- As of the time the underlying data was provided, Pewlett-Hackard employeed a total of 240,124 employees, 72,458 of whom meet the criteria for approaching retirement elgibility age - a very significant percentage (30.18%) of the company's total workforce.

    -- Active Employees:
    
![Active Employee Count](/Images/active_emp_count.png)

    -- Approaching Retirement Elgibility Employees:
    
![Retirement Elgible Employee Count](/Images/retirement_elgible_emp_count.png)

### Breakdown by Current Titles

- Of the employees approaching retirement elgibility age, 25,916 currently hold the title "Senior Engineer" and 24,926 hold the title "Senior Staff" - however, the percentage of total employees within each Job Title approaching retirement elgibility is consistent across nearly all Job Titles, at approximately 30%.  The following table details the percentage of total employees by Title who are approaching retirement elgibility age:
    
![percentages_by_title](/Images/percentages_by_title.png)

### Breakdown by Department

- The percentage of total employees within each Department approaching retirement elgibility is consistent across all Departments, at approximately 30%.  The following table details the percentage of total employees by Department who are approaching retirement elgibility age:
    
![percentages_by_title](/Images/percentages_by_dept.png)


### Mentorship Elgible Employees

- Based on the current Mentorship Elgibility criteria, there are very few employees elgible to serve as Mentors, in relation to the number of employees approaching retirement elgibility age:
    
![Count of Elgible Mentors](/Images/count_of_mentorship_elg_employees.png)

## Sumary
In Summary, as a result of our analysis of the provided data, we would draw attention to the following Conclusions:

### Roles to be Filled

- As stated previously, based on the critieria that was provided, there are 72,458 employees who will meet the retirement elgibility age critera; a detailed breakdown of those potential vacancies by Department and current Title is as follows:

![Count of Retirement Elgible Employees by Dept and Title](/Images/count_of_reitiring_emp_by_dept_title_sql.png)

![Count of Retirement Elgible Employees by Dept and Title](/Images/count_of_reitiring_emp_by_dept_title.png)

### Mentorship Elgible Employees

- As mentioned previously, based on the current Mentorship Elgibility criteria, there are very few employees elgible to serve as Mentors in relation to the number of employees approaching retirement elgibility age and the corresponding number of vacancies that are likely to need to be filled.  A list detailing the number of employees elgible to serve as Mentors and their current Department and Title is as follows:

![Count of Retirement Elgible Employees by Dept and Title](/Images/count_of_reitiring_emp_by_dept_title_sql.png)

![Count of Elgible Mentors by Dept and Title](/Images/mentors_by_dept_title.png)

