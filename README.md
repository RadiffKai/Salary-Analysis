# Salary-Analysis
 The main reason for this analysis was;
To understand the data science job market, I asked the following:  
Do more skills get you better pay?  
What’s the salary for data jobs in different regions?  
What are the top skills of data professionals?  
What’s the pay for the top 10 skills?

## Skills used
 Pivot Tables  
 Pivot Charts  
 DAX (Data Analysis Expressions)  
 Power Query  
 Power Pivot 
 
 I used Power query(ETL)phase, the data set is from data_jobs.... i used it two create two queries;  
  First one with all the data jobs information.
 The second listing the skills for each job ID.
 Then, I transformed each query by changing column types, removing unnecessary columns, cleaning text to eliminate specific words,     and trimming excess whitespace.
 
 <img width="920" height="269" alt="Screenshot 2026-09-08 234432" src="https://github.com/user-attachments/assets/e529e4b8-538b-42e5-a6d9-0370382c93d9" />  
 
 Loaded the powe query to a pivot table and pivot chart to gain insights on the most sort skill per job title and country as shown in using slicers  

 ### Power pivot
 i used it to model  the data 1 is to many relationship, used both implicit and explicit measures to achieve my analysis goal eg skill count(total skills divided by the all the jobs ) 
 
<img width="938" height="475" alt="Screenshot 2026-09-08 235033" src="https://github.com/user-attachments/assets/11692ee9-75a3-4e85-b63b-8b95c0999593" />  

There is a positive correlation between the number of skills requested in job postings and the median salary, particularly in roles like Senior Data Engineer and Data Scientist.

 Roles that require fewer skills, like Business Analyst, tend to offer lower salaries, suggesting that more specialized skill sets command higher market value.  
 
<img width="282" height="202" alt="Screenshot 2026-09-08 234414" src="https://github.com/user-attachments/assets/3e29ca8f-218e-4951-bee4-92cbd9ee8f06" />
<img width="388" height="236" alt="Screenshot 2026-09-08 234401" src="https://github.com/user-attachments/assets/cbf6dd2b-91ba-4445-ba30-24e054d16cc9" />  
This is the basically what is done in this analysis for more info about the project [salary.analysis.xlsx](salary.analysis.xlsx)


 
