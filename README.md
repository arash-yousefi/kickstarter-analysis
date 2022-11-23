
## 1.Overview of Project 

Louise, who wants to start a crowdfunding campaign to help fund her play, *Fever*. She's estimating a budget of over $10,000 and is understandably hesitant about jumping into her first fundraising
&Using Excel to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful.
these 2 challenges visualize campaign outcomes based on their launch dates and their funding goals.


### Purpose
- Louise wants to know how different campaigns proceed in relation to their launch dates and their funding goals.


## 2.Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
- After adding new coloumn (Year) to Kickstarter select then choose all coloumn and from insert->Pivotchart after choosing coloumn,rows, filtern value then right-click on "Change Chart Type" to line
### Analysis of Outcomes Based on Goals
- select "Goal", "Percentage successful ", "Percentage failed ","Percentage canceled " =>insert=>line table
### Challenges and Difficulties Encountered

 The only challenge I encountered was that in some parts of activity the steps were not very clear, for example:

	>  In the "Years" column, use the YEAR() function to extract the year from the “Date Created Conversion” column.

Solution: I used the Slack to find out the answer that it was provided in the :02-Ask the Class.

	>  Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 3, and on the "Subcategory" column using "plays" as the criteria.

Solution: I used SHOW HINT section.


## 3.Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?
 We can see:								       
 - i. The most successful theater is performing in May.              
 - ii. On October the theater cancelation is zero.  

#### What can you conclude about the Outcomes based on Goals?

- The “plays “with goal between $45000 to $49999:
performed once and that was failed. In the “plays: with goal less than $1000 we can see the most difference between successful percentage and failed percentage, which is:
“+ 51.61%”.


#### What are some limitations of this dataset?
- i.	Percentage Difference (successful - failed) could have been added to this dataset.

- ii.	Live outcome has not been selected.

- iii.	Goals are limited to certain amounts.


#### What are some other possible tables and/or graphs that we could create?
- i.	Outcome Based on Deadline
- ii.	Outcome base on Pledged 
- iii.	Outcome Based Parent Category or Country


  
