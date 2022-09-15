# Kickstarter Analysis

## Overview of Project
Louise is a future-proof playwright who started a crowdfunding campaign to finance her play. The campaign has approached its goal of fundraising in a very short time. Louise's expectation from us is that we analyze the performances of campaigns similar to her own regarding the launch dates and financing targets and ensure that they come to life in her eyes. In this project, we analyzed data on crowdfunding campaigns from 2009 to 2017.

### Purpose
The purpose of this project is to examine if there are differentiators that can make a project campaign successful, if so, what is going on and especially filtering them on the basis of games. In our analysis, we try to help with whether there is a link between successful campaigns and their launch dates and goals. With this analysis, we aim to show Louise how her campaign is performing compared to other similar campaigns.

## Analysis and Challenges
Fundraising analysis with the available data of the past time takes place in two steps. First are the results according to the objectives of the campaign, with the evaluation of the results based on the launch date (years and months).

### Analysis Outcomes Based on Launch Date
In our initial analysis, we filtered the results of the campaigns through theatrical campaigns. In order to analyze these data, we created a pivot chart. In order to carry out this analysis, we had to determine the years. We added a new column and used the years function in excel based on the start date of each campaign. Next, we created the pivot table from the kickstarter datasheet and did our analysis on a month-to-month basis using the theater category and the years filter.

<img width="374" alt="Theatre_Outcomes_Based_on_Launch" src="https://user-images.githubusercontent.com/26927158/190499561-a0fff86f-01c2-4ed5-97c4-3c651be6ab40.png">

With the help of the pivot table, we created a line chart to display the theater results by launch date.

<img width="857" alt="Theatre_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/26927158/190500210-8615210b-6aa4-45f6-aabc-4001eaf4977c.png">

### Analysis of Outcomes Based on Goals
In this analysis, we evaluated the results of the campaigns according to the fundraising goals and games campaigns by subcategory. For this, we aimed to create a new table and analyzed the successful, unsuccessful and canceled campaigns on the basis of the games subcategory, within the framework of the number target amounts of the campaigns, using the COUNTIFS() excel function. Using this data, we calculated the percentages of successful, unsuccessful and canceled campaigns with the help of our total number of projects. After analyzing all of our data in our table, we have completed the visualization of our results based on goals with the help of the line chart. You can see this line graph below.

<img width="1151" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/26927158/190502613-3e4424d0-0d32-43eb-aee1-be910a5c3757.png">

### Challenges and Difficulties Encountered
In this analysis, it was necessary to add new columns to our existing data set. In fact, I can say that it was useful, the reason is that I had the opportunity to learn excel formulas that I had not used before. First of all, it was very difficult to add the start and end dates of the launches as columns. I can say it took a long time. We had to use the date function to write the start and end data we had in date format. It took me a long time to use it and understand how to use it.
Although I had no difficulty in creating the table for visualizations, when the figures in the table were not visible in the analysis, I could see the table when I saved it to the computer. I learned how to fix this problem.
In the pivot table, the months appeared in the form of numbers. No matter how hard I tried, I couldn't find an easy way and the formulas made it harder, but finally I was able to solve my problem.
COUNTIFS, another excel function, was a formula that I did not know how to use before. It would be correct to say that it made it easy for me to learn how to analyze on the basis of intervals.
