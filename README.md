# Kickstarting with Excel
Module 1 An Analysis of Kickstarter Campaigns Project

## Overview of Project & Purpose
The purpose of this project was to introduce us to different ways of using Excel for analysis of a kickstarter campaign for theatrical plays. The main task was to filter through a data set with thousands of kickstarter campaigns and find data that would be helpful to Louise who is running a campaign for her play *Fever*. Here my analysis shows trends about the outcomes of kickstarter campaigns in the plays subcategory based on launch date and whether or not the goal was achieved.   
## Analysis and Challenges

### Analysis of Theater Outcomes Based on Launch Date
For this analysis, I created a pivot table of data that counted the number of occurances of successful, failed, or canceled *theater* kickstarter campaigns sorted by launch month for all years of avaliable data. The following graph visualizes the data by showing launch month versus the number of occurances of theater kickstarter campaigns that were successs, failed, or canceled.

![alt text](https://github.com/nsmeltz/Module-1-Challenge-Kickstarter-Analysis/blob/521a039cdbd396ed769f3958b1623011e3e78f9e/Theater_Outcomes_vs_Launch.png)

### Analysis of Play Outcomes Based on Goals
For this analysis, I created a table of data that counted the number of occurances of successful, failed, or canceled kickstarted campaigns for *plays* using the COUNTIFS function in Excel. The following graph visualizes the data by showing goal amount range versus the percentage of *play* kickstarter campaigns that were successs, failed, or canceled. Goals were sorted into ranges starting at less than $1000 and ending at greater than $50,000. Each data point is associated with the appropriate goal range and plotted according to percentage. 

![alt text](https://github.com/nsmeltz/Module-1-Challenge-Kickstarter-Analysis/blob/012e669ec81cc741ade69615a31be974ceb10417/Play_Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The biggest challenges with a large data set like this is to make sure that you are calling data from the correct columns for anlaysis and filtering for only the data that applies to the category/subcategory you want to target. At first I forgot to filter by subcategory(plays) in the Outcomes Based on Goals analysis which really could have messed up my analysis. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The majority of successful theater kickstarters were in May, but the number of successful campaigns quickly tapers off through out the rest of the year. The number of canceled campains does not show a strong trend with month of launch date, but there is a gap in the data for October. This gap interests me because this means that there were no theater campaigns that were cancelled in the month of October which is confusing because there should be a point for October at 0. This point does not show because the cell in the pivot table does not have a value in it so the pivot chart has no data to plot. 

- What can you conclude about the Outcomes based on Goals?
There were no canceled play kickstarter campaigns, so all campaigns either were sucessfull or failed. The most sucessful campaigns have goals of <$4999 or $35,000 to $44,999.

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
