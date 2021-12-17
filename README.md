# Pewlett-Hackard-Analysis

## Overview
To help Bobby present to his manager about the number of retiring employees coming in the near future by title.  To also identify the employees who are eligible for the mentorship program.  Both done using SQL and multiple CSV tables.  

## Results of the Coming Expected Retirements
Below is a breakout of the 'silver tsunami' table for detail followed by bullets.

![Retiring Titles](https://user-images.githubusercontent.com/92898919/146584778-1a2463d5-599c-4baa-bfe9-c0d04c56c9db.png)
* There are over 70,000 workers that are expected to retire in the 'silver tsunami'
* The largest position that will need to be replaced will be Senior Engineer
* Most postions have in thier title 'Senior', 'Leader' or 'Manager' suggesting leadership/managerial roles need to be replaced


## Results of the Mentorship Program
The excel workbook 'mentorhsip_eligibility' displays a list of all the workers that fit the criteria for the mentorship program.
* There are over 18,000 employees who fit the mentorship program criteria
* These also line up with the ones who will retire so maybe lowering the birth date could provide more long term mentorship

## Summary
There are over 70,000 employees that will retire soon in the 'silver tsunami'.  The breakout by title is shown above in the table.  There are over 240,000 employees at the Company so with a little more than a quarter leaving they should be able to backfill the positions.  A query was done to check what percentage of each title will be left after the silver tsunami.  This result is shown below.  There are many individuals at every title that can handle the turnover.

![All Employees](https://user-images.githubusercontent.com/92898919/146601282-7be8bd1c-8103-460f-ac46-be863383b502.png)

An additional query could be to find the summation of all the salaries of the employees who are looking to retire to help them quantify how much money they have to backfill the positions.  
