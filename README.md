# Pewlett-Hackard-Analysis

## Overview of The Analysis

### Background

Bobby's Manager has given assignment to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, write a report that summarizes analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

### Purpose

The purpose of this analysis is to deliver:

* Deliverable 1: The Number of Retiring Employees by Title

* Deliverable 2: The Employees Eligible for the Mentorship Program

* Deliverable 3: A written report on the employee database analysis (README.md)


## Result

* The retirment_titles table shows employees eligible for retirement and how long they have been worked at each position over the course of their career.

  ![Retirement Titles Table](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/retirement_title.png)

* The unique titles table shows the most recent title for employees of their retirment age.

  ![Unique Titles Table](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/unique_titles.png)

* Our retiring_titles shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) are senior staff.

  ![Retiring Titles Table](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/retiring_title.png)

* In mentorship_eligibility table, if we closely observe the title column we can see most of the employees has senior title.

  ![Mentorship Eligibility Table](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/mentorship_eligibility.png)
  

## Summary

* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

  90,398 roles are in urgent need to be filled out as soon as the workforce starts retiring at any given time. More than half of these are senior staff. 

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

  No, we have only 1,940 employees who are eligible to participate in a mentorship program. Which will create a lot of workload on each mentor. 

 * By breaking down the mentorship eligible employees by department in the query below, we can see that the employees are proportionally spread to the employees that are retiring but there is still too few employees to mentor the retiring employees.
 
   ![Mentorship Eligibilty by Department](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/mentorship_eligible_emp_by_dept.png)


* If we consider to extend the mentorship eligibility by 1 year to employees born in 1964 there are 19,905 eligible employees; which is more manageable. In the query for mentorship_eligibility we need to change start year to 1964 in 'WHERE' clause of the query for extending the eligible employees and visualize the department breakdown of the extended filter is shown below.
  
  ![Mentorship Eligibility by lowring 1 year](https://github.com/rachanamule/Pewlett-Hackard-Analysis/blob/4ae47f9f2ce3378e149e02fafe5ba02c03757c05/mentorship_eligibility_from_1964.png)
