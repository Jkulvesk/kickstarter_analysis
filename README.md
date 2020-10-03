# Module 1 Challenge - Kickstarting with Excel

## Overview of Project
This challenge demonstrates my understanding of how to manipulate and visualize data using Excel. For this challenge I used lookups, pivot tables, formulas and charts. Using the kickstarter campaign spreadsheet I visualized campaign outcomes based on their launch dates and their funding goal.

### Purpose

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For this analysis, I created a pivot table and filtered on theater. I also filtered the time period to only show months by right clicking on the period and selecting months. I reordered the columns to show successful, failed and canceled outcomes and then created a chart based on the pivot table. Here is a screenshot of the chart.

https://user-images.githubusercontent.com/72076683/94998251-19ad4e00-0576-11eb-8ffe-5693a4db602a.png

### Analysis of Outcomes Based on Goals
For this analysis, I inputed the ranges and then grabbed the correct values (plays, goal ranges and goal success factors) using the countifs function. I then summed the results and created percentages of success, failure and canceled outcomes. Then I created a chart to visually show the results. Here is a screenshot of the chart.

https://user-images.githubusercontent.com/72076683/94998305-8cb6c480-0576-11eb-84d5-45feaf2934eb.png

### Challenges and Difficulties Encountered
For the outcomes based on goals chart, I initially did not include 'plays' into the formula. I quickly realized this when my chart did not match the image. I also had to Google how to remove the pivot descriptors from the charts. Versions of Excel I've worked with in the past never did that. I also had to Google how to do a between range for the countif formula.
https://www.extendoffice.com/documents/excel/2412-excel-count-cells-between-two-values.html

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The most successful launch periods, based on outcome (was pledged amount equal to or greater than goal), are during May - July.
The time of year does not have much of an impact on canceled theater kickstarters with the exception of October. I would want to understand why October is never canceled.

- What can you conclude about the Outcomes based on Goals?
The most successful campaigns, based on meeting the goal, are those that have a goal of under $1000. Campaigns where the success is greater than the failure is where the goals are less than $15,000 (with a greater success rate of less than $5000) and between $35,000 and $44,999

- What are some limitations of this dataset?
We are only looking at the number of outcomes, not the financial impact. If you look at the dollars pledged overall for theater kickstarters, the most successful months are April, September and October. The financial success in terms of dollars raised does not come through when only looking at number of outcomes based on whether the funding goal was met or not.

- What are some other possible tables and/or graphs that we could create?
Dollars raised by month by campaign type/subtype to see what the most financial successful campaigns were, and then I'd look at the reason for those by looking at the average number of backers, and the average dollar per backer. 
I'm also curious why no campaigns are canceled in October, so I would look at what kind of campaigns those are compared to other months.

To better understand where Louise should set the goal for her campaigns, I'd look at number of backers, average amount of backers and whether those campaigns were spotlighted. I'd run this analysis by campaign category and subcatory to propose goals based on funds raised based on average historical performance.
