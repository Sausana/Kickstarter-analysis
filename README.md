# Kickstarting with Excel

## Overview of Project 
Using the kickStarter dataset,i am analysing for Louise  how different campaigns fared in relation to their launch dates and their funding goals.This will help in deciding when would be a good time to launch a campaign and the goal to be set for the campaign.
### Purpose
The purpose of the project is to help  analyze for Louise how different campaigns fared in relation to their launch dates and their funding goals.

### Analysis of Outcomes Based on Launch Date
The Category and Subcategory column was split into two distinct columns: 'Parent category' and 'Subcategory' which gave additional data to use for analysis. A new column was created for 'Date Created conversion' using data from Column J as it contained Unix timestamps. A formula was used to convert these timestamps into a day-month-year format. Another column named 'Years' was created to extract the year from the 'Date Created Conversion' column using the Year () function. The Year Column was created to analyze the outcome based on years.To Analyze the data for “Outcomes based on Launch date “, for theater, a filter was applied to ‘Parent category’
![image_name](C:\Users\gksus\Homework\Week 2 Kickstarter Challenge\Kickstarter-analysis\Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
For Outcomes based on Goals sheet, the number of successful, failed and canceled shows were calculated using COUNTIFS function, Total projects were calculated using SUM function () and  the percentage of successful, failed and canceled shows were calculated by dividing Sum by total and applying the percentage function to the result. The campaign outcomes were sorted in descending order so "successful" is first. The Pivot table showed ‘Live’ shows too and it was unchecked using the ‘count of outcomes’ filter to show only necessary information
![image_name](C:\Users\gksus\Homework\Week 2 Kickstarter Challenge\Kickstarter-analysis\Outcomes_vs_Goal.png)
### Challenges and Difficulties Encountered
I had an issue with the Pivot chart wherein the Goal was not sorted. I right clicked the cell and used ‘Move ’option to place the Goals in order.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

•	The most successful campaigns were in the month of May.
•	The least successful campaign was in the month of December and could be due to the holiday season.
•	There were no canceled campaigns in the month of October.

- What can you conclude about the Outcomes based on Goals?
•	The percentage of successful plays was in the range of around 1000$ and less than 5000$
•	The failed campaign for plays was around 45000$ to 49000$.

- What are some limitations of this dataset?
The limitation is that the dataset is small and so can’t make concrete decisions based on it. 
- What are some other possible tables and/or graphs that we could create?
 Another table that can be created is Outcomes vs Country .I used a Stacked column start for this analysis.Below is the table and the chart
 ![image_name](C:\Users\gksus\Homework\Week 2 Kickstarter Challenge\Kickstarter-analysis\Outcome_vs_Country)


