# Pewlett-Hackard-Analysis
## Analysis Overview
The purpose of this analysis is to determine if there are enough employees eligible for the mentorship program that Pewlett-Hackard is looking into implenting. The company may begin experiencing a "silver tsunami", where a large number of their employees will enter retirement at around the same time, leaving behind vacated positions. To prepare for this, we looked into how many employees are retiring per job position. We then looked into employee data to review who would be eligible to participate in a mentorship program, to prepare these current employees to take over the newly-vacated positions.

## Resources
  * Software: PostgreSQL 11.

## Results
Upon analysis of the data provided by Pewlett-Hackard, we retrieved the number of employees who are retiring, and sorted by position title.

![retiring_titles](https://user-images.githubusercontent.com/106129195/181832970-6a10ea5c-af6f-48b2-9512-60bed2d1774c.png)
###### The number of employees retiring per position title.

After pulling the number of employees who are retiring, sorted by position title, we investigated mentorship eligibility in the company. Our parameters were employees who are currently employed with Pewlett-Hackard, and born in 1965.

![mentorship_eligibility](https://user-images.githubusercontent.com/106129195/181834295-ee4a6e69-09ce-4bfb-9f69-e6349c892e2a.png)
###### The number of employees eligible for the mentorship program, per position title.

Reviewing these two lists, there are a number of conclusions we can draw.
* The largest number of positions being vacated via retirement are the Senior Engineers and the Senior Staff. These are more than 20,000 employees each.
* Comparing the number to those eligible for the mentorship program, the numbers are much smaller. There are no positions where more than 1,000 employees are eligible for the mentorship program.
* We can also see that there are no employees eligible to participate in the mentorship program for the position of manager.
* To address the large gap of eligible employees to the retirement-ready employees, Pewlett-Hackard may want to look into expanding their eligibility requirements for the program, and/or begin the process of hiring more employees for those positions.


## Summary
One may wonder how many roles will need to be filled as the "silver tsunami" begins to make an impact. To get a broad look into this, let us view how many retiring positions in total there are.

![Total_Count](https://user-images.githubusercontent.com/106129195/181840610-64173629-164f-4a87-b201-b0fc74ce6935.png)

Now, let us look at the total number of employees eligibile for the mentorship program.

![Total_Eligibility_Count](https://user-images.githubusercontent.com/106129195/181840667-f30f267f-0318-4276-a511-b457514d2b23.png)

There are 72,458 employees retiring, but only 1,549 employees eligible for the mentorship program. That would leave 70,909 vacated positions. This would put immense stress on Pewlett-Hackard to have so many vacancies, and could drastically affect productivity for themselves and their clients. While there is a large number of qualified, retirement-ready employees to mentor the next generation of Pewlett-Hackard employees, there are not enough employees to fill those positions once the retired employees take their leave.
