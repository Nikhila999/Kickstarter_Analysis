# Kickstarting with Excel

## Overview of Project

Louise is interested in launching a play *Fever* and it is very close to its fundraising goal. She wants to analyze crowdfunding data and know any specific factors that make the kickstarter campaigns successful.

### Purpose
The purpose of the analyses is to help Louise make an informed decision on the best time to launch her play and if the fundraising goals she has set makes it successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analyze the number of successful, failed and canceled campaigns by months, create a pivot table and a line chart from Kickstarter workbook. Filter the Parent category to *theater* and remove *live* outcomes.
Please look at the image below, the blue line represents the number of successful campaigns, orange line represents the failed campaigns and grey line represent canceled campaigns.
-- insert an image
From the image we can say that,
* May is favorable month to launch a theatre project (i.e. play) and December is an unfavorable month.
* May, June, July, August and October have around the same number of failed campaigns.
* January has the highest number of canceled campaigns and the rest of the months except for October have similar number of canceled campaigns.

### Analysis of Outcomes Based on Goals
To analyze the outcomes based on goals, first, define goal amount ranges (here, we are creating the intervals of $5000) and calculate number of successful, failed and canceled campaigns along with respective percentages. Create a line graph with percentage successful and percentage failed campaigns to proceed with the analysis.
Please look at the image below, the blue line represents the percentage successful campaigns based on goal amount range and the orange line represents the percentage failed campaigns.
-- insert an image
From the image we can say that,
* More successful campaigns have smaller goal amounts, when the goal amount is less than $5000 there is more than 72% chance of it being successful.
* As the goal amount increases the chances of a campaign to fail also increases. 
* There is an anomoly for the goal amounts between 35k-45k, we need to do more analysis to know if these is an expection or a valid data points.

### Challenges and Difficulties Encountered

* When formatting a graph, it is best practice to use same colors for measures to keep it consistent. I have decided to use blue color for successful and orange for failed. However, the default color palate for 'Outcomes Based on Goals' graph is using green/blue colors. I couldn't figure out where to change the colors until i explored all the options on menu ribbon. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    - We  have found that the May month is most sucessful in launching theatre kickstarter campaigns. Also, May, June, July, August and October months have similar number of failed theatre kickstarter campaings.
    - Looking at the line graph we can also conclude that in may month the number of successful campaings are more than double the number of failed theatre kickstarter campaigns

- What can you conclude about the Outcomes based on Goals?

    - Looking at the Outcomes based in Goals line graph, we can conclude that,
        1. The highest number of successful campaigns are funded with goals less than $1000 and as the goal amount starts to increase the success of the campaign is reduced except for the goal amounts between 35k - 45k.
        2. Also, there are no successful campagins for goal amount between 45k-50k and there are 294 failed campaigns.

- What are some limitations of this dataset?
    - Dataset we are working on could be incomplete, notice that the data is starting from 2009.
    - There are a few outliers in the data, we do not know to account for outliers in data
    - We do not know the source of data. So, we do not know how to address and take measures to reduce bias in the crowdfunding data.


- What are some other possible tables and/or graphs that we could create?
    - There are some outliers in the dataset, using the box plots we could easily address the ouliers present in the dataset and make an informed decision.
    - In Outcomes based on Goals line graph, looking just at the percentage successful and percentage failed may not give the complete analysis. Because, goal amount between 35k and 45k has 66.7% success rate and 33.3 % failure, however comparing the number of successful(6) and failed(3) campaigns to total number of successful(694) and failed campaigns(648) is very low. So, having a tabular report next to the line graph would be more informative.
