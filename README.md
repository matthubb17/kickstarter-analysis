# Kickstarting with Excel

## Overview of Project: 

#### Louise, an up and coming playwright, would like to set up a crowdfunding campaign to help fund her play "Fever". The purpose of this project was to analyze Kickstarter data for Louise in order to help her to understand how previous kickstarter fundraising campagins have performed. Louise had anticipated a budget of $10,000 for her campaign. I approached this analysis by taking a look at the performance as it related to launch date along with funding goal.

## Analysis and Challenges:

### Analysis of Outcomes Based on Launch Date

![Image of Theater Outcomes based on Launch Date](https://github.com/matthubb17/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

##### The chart above can be used as a visualization of outcomes for the theater category specifically broken out by month. 
##### This chart was created by generating a pivot table with Month as the row lables, and the column labels being the outcomes. In order to have this pivot table correctly display the months I first needed to create an additional column within our data sheet in order to convert our date data into a readable format. By using the proper formulas within excel I was able to create a column that simply displayed the year in which the campaign occurred.



### Analysis of Outcomes Based on Goal

![Image of Outcomes Based on Goals](https://github.com/matthubb17/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

##### The chart above can be used as a visualization of campaign success, failed, and canceled rates as they pertain to the set $ goal amount for a given camapign.

### Challenges and Difficulties Encountered

## Results:

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - May was the most successful month to launch a Kickstarter campaign within the theater category.
  - December saw the fewest successful campaigns within the theater category.


- What can you conclude about the Outcomes based on Goals?
  - You are more likley to have a successful campaign if you limit your goal to less than $5,000. While there are other ranges that show a relatively high rate of success, this data is lover volume.
     - There are other factors at play here that are influencing success rate, as we do see fairly high success rates for $35,000 - $45,000.

- What are some limitations of this dataset?

  - The data for this project is limited as it is only a small amount of data for a set period of time. In order to have more reliable info you would most likely want to expand your dataset to look at data over a longer period of time. In addition, the number of countries that were include in this data set could be expanded.

- What are some other possible tables and/or graphs that we could create?
  - One analysis that I think would be benificial to look at would be to analyze the relationship between the success rate and the quantiy of backers. This would help us to better understand if there is an impact to the outcome based on the size of the campaign.
