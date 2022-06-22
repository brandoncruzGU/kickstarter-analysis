# Kickstarter Challenge

## Project Overview

Louise is interested in comparing the success of other theatre campaigns based on their launch dates and funding goals. This analysis uses Microsoft Excel to creates tables and charts to display the outcomes of the various launch dates and funding goals.

## Analysis and Challenges
### Theatre Outcomes Based on Launch Date
First, I created a Pivot table to show the amount of successful, failed, and canceled campaigns for each month within the theater category. I then created a line chart to show the trend for each of the different campaign outcomes throughout the year.

Initially, I didn’t have the variables grouped together and I struggled to see the right data table. When I used the hint, I was able to see the correct table to create the line chart.

### Outcomes Based on Goal
I used the “COUNTIFS” function to count the number of successful, failed, and canceled campaigns that fell within a specified funding goal range and the “plays” subcategory. Next, I found the sum of the failed and successful projects using the “SUM” function. I then set up an equation to find the percentage of successful and failed campaigns within each funding goal range.

One challenge that I faced was using the Fill series option to auto populate the formula in the column while maintaining the same reference cell range. This defeated the purpose of using the fill option because I would have to make a significant number of edits. I ended up changing my process and decided to copy equations directly from the formula bar and pasted them in each cell and made the appropriate changes throughout. Although this may have not been the most efficient method, this process did result in fewer changes than my initial approach. 

## Results
### Theatre Outcomes Based on Launch Date
More successful theatre campaigns launch in May, June, and July. Louise should aim to launch her campaign in these months to increase the likelihood of success.

The number of successful campaigns decreases towards the end of the year-with a continual decrease until January. Louise should avoid launching her campaign between October and December.

### Outcomes Based on Goal
Campaigns with goals less than $1,000 are much more likely to be successful. The percentage of successful campaigns remains greater than failed campaigns until we reach about $15,000. Setting a campaign goal that is less that $1,000 will likely increase its success. 

### Limitations
One limitation of this dataset is that the ranges used for the funding goals may not have a sufficient sample size to provide valid recommendations. Certain ranges have less than ten campaigns total which may not be a sufficient sample size to predict the campaigns outcome.

### Recommendations
Another chart that we can look at is the number of successful and failed campaigns based on the average amount of pledges. This will help Louise understand how many people she needs to back the campaign and how much to ask for.
