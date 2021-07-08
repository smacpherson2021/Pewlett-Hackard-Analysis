# Pewlett-Hackard-Analysis

## Overview of the Pewlett Hackard analysis: 

The company Pewlett Hackard, with several thousand employees, has requested a workforce planning analysis on employee retirements to help determine the number of expected employees retiring per title. Employees born between 1952 and 1955 are expected to retire shortly. They also wish to identify employees to participate in a mentorship program who currently meet the eligiblility requirment of being born in 1965. 

## Results:

* ***Retirement Titles*** <br />
  The retirement titles table shows the list of employees titles who were born between '1952-01-01' and '1955-12-31'. This table may contain more then one record per employee for employees that had changes in either their department or title. 
![retirement_titles_query_results.png](https://github.com/smacpherson2021/Pewlett-Hackard-Analysis/blob/main/Images/retirement_titles_query_results.png)

* ***Unique Titles*** <br />
  The unique titles table shows the list of employees titles who were born between '1952-01-01' and '1955-12-31' but only shows records for the latest unique title.
![unique_titles_query_results.png](https://github.com/smacpherson2021/Pewlett-Hackard-Analysis/blob/main/Images/unique_titles_query_results.png)

* ***Retiring Titles*** <br />
  The retiring titles table shows number of employees by each tile for all the employees born between '1952-01-01' and '1955-12-31'. 
![retirement_titles_query_results.png](https://github.com/smacpherson2021/Pewlett-Hackard-Analysis/blob/main/Images/retiring_titles_query_results.png)

* ***Mentorship Eligibity*** <br />
  The mentorship eligibility table shows the list of employees that are eligible for mentorship based on the criteria they both currently employeed with the company and were born in the year 1965
![retirement_titles_query_results.png](https://github.com/smacpherson2021/Pewlett-Hackard-Analysis/blob/main/Images/mentorship_eligibility_query_results.png)


## Summary:

This analysis helps answer the following questions:<br />

How many roles will need to be filled as the "silver tsunami" begins to make an impact?<br />
* Over the next 4 years about 90,000 roles, or about 20,000-25,000 roles per year,  will need to be filled due to upcoming retirements.<br />
  
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?<br />
* There are enough retirement-ready employees to mentor all the employees eligible for mentorship except for the position of Manager. There are currently only two retirement-ready Managers available to be mentors.<br />
  
Additional queries that may provide more insight into the upcoming "silver tsunami":
* Determine how many retirement-ready employees there are, by each tile, by each separate year from 1952 to 1955. By breaking apart this number by year, it will help determine if there is a particular time when a particular position might be most impacted by retirements or if the retirements are consistant year over year for all positions.  
* Determine the number of eligible employees for mentorship for employees born in years other then 1965. By expanding the age range of employees eligible for mentorship this can also help us determine if current list of retirement-ready employees is enough to expand the program beyong employees born in 1965.
