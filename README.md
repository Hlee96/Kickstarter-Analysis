# Kickstarter-Analysis
Perform analysis on kickstarter data top uncover trends
# Kickstarter Analysis
## Overview
The project is for Louise who is starting a fundraising campaign to fund her play “Fever”, with a budget of $10,000. Since there are over 4,000 data points in the spreadsheet, Louise needed a data analyst to help her answer the questions she needed. By using different Excel tools and formulas to generate conclusions and chart, Louise was able to understand what makes a fundraising campaign successful.
## Purpose
The purpose of the analysis is to help Louise determine what makes a fundraising campaign successful, so she can have a successful campaign to raise the $10,000 for her play “Fever”.  By analyzing different categories of campaigns, length of campaign duration, goals, pledges, and the outcome for each campaign, we can draw conclusions to help Louise make the right decisions for her campaign to be successful.
## Analysis and Challenges
The analysis was performed through:
-	Filtering and sorting through the columns to organize the amount of goal and pledge. 
-	Conditional formatting the outcomes by successful, failed, live, and canceled.
-	Changing the date format for date created and ended.
-	Separating the parent and subcategories into two different columns to filter by each column.
-	Creating pivot tables and charts for analysis.
-	Using the VLOOKUP function to lookup specific names and words.
-	Using the nested count function (COUNTIFS) to count the outcomes.
-	Filter the PivotCharts by the parent category, subcategory, country, etc. 
-	Challenge was inserting the correct range for the goal in the “Outcomes Based on Goals” sheet.
-	After watching the video on using the COUNTIFS function, I was able to perform the formula to get the results required.
##### Analysis of Outcomes based on Launch Date
The analysis was performed through:
-	Creating a pivot chart for Theater Outcomes Based on Launch Date. Filter the parent category of theater. Organizing the columns to start with the successful outcomes to canceled. 
-	Creating a line chart with markers titled “Theater Outcomes Based on Launch Date” based on the pivot table created.
-	Putting the number of outcomes in the Y axis for the ‘successful’, ‘failed’, ‘canceled’.
-	Putting the count of outcomes by month in the x axis to show the change over time.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108282027/177367598-6591ca15-00c2-4772-b01a-f5631fd4c80b.png)
## Analysis of Outcomes based on Goals
The analysis was performed through:
-	Creating new header for columns A-H, by the range of goal, followed by the number of ‘successful’, ‘failed’, ‘canceled’, column for the total, with the percentage of columns B-D.
-	Using the COUNTIFS function to filter by the goal, outcome, subcategory (plays).
-	Generating the count of outcome based on ‘successful’, ‘failed’, ‘canceled’.
-	Generating the percentage of each outcome.
-	Based on the information that was filled within the table, generating a line chart to show the percentage of each outcome based on the range of the goal. 
-	Goal range on the X axis and Percentage of each outcome range in the Y axis.
![Outcomes_vs_goals](https://user-images.githubusercontent.com/108282027/177367483-6fc25020-780a-44b5-b599-e10deab4b6d6.png)
## Results
o	The highest count number of successful outcomes based on plays had the goal range of $1,000-$4,9999. With the count of 388 successes out of 534 total projects. Which leads to 73% successful rate.
o	Highest successful percentage had the goal of less than $1,000 with a success rate of 76%.
o	Since Louise’s play “fever” budget is set at $10,000 she will have a lower success rate from the previous ranges listed. Fever budget will fall under the $10,000 to $14,999 range which has 54% success rate. 
Outcome based on Launch Date
o	There is a spike in the number of successful outcomes for the “Theater” Parent category from the month April to May (71 to 111, increase of 40 number of successful outcomes). 
o	Louise should look to have her fundraising campaign between the months of April through July which holds the highest number of successful fundraising campaigns.
o	Louise should avoid having a campaign in the month of January, it has the lowest number of successes but also the highest number of cancellations.  
o	There is a slight positive correlation between the high number of successful outcomes vs. the number of failures.
Summary
o	Some limitations were that there is no clear explanation of the different headers. Such as the meaning of backers count and spotlight.
o	If Louise wants to hold the play just in the US, it is not necessary to have other datasets of different countries, since it can interfere with the analysis and draw unwanted outliers to the calculation of mean, median, and standard deviation.
o	The data set should have included only the parent category of Parent and its sub. Since Louise is only focusing on Theater and plays, having multiple datasets not related to the purpose of the analysis can be time consuming going through the data cleaning process. 
o	The box and whisker plot can be used to eliminate specific outliers for the range of goals. It will help Louise understand on what is the mean and median of the goal that results in a successful campaign outcome. 
o	A stacked bar chart can be used in the Theater Outcomes based on Launch Date sheet to determine which month had the most successful outcomes in comparison to the failed and canceled. It can help Louise to visualize the proportion and ratio in one bar. 


