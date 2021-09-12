# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to contextualize the performance of Louise's recent Kickstarter campaign for the play, Fever. By analyzing the outcomes of past campaigns in the theater category based on their unique launch dates and fundraising goals, we are able to better understand how Louise's campaign fared in relation to other, similar campaigns.

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date
I performed this analysis by creating a pivot chart which displays the the number of successful, failed, and cancelled theater campaigns based on the month in which they were launched.
![image_name](https://github.com/krystinmckee/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
I performed this analysis by sorting campaign data from the "plays" subcategory into bins based on their stated campaign goal. I then determined the percentage of successful, failed, and canceled campaigns within each bin (goal interval), and created a graph to visualize the data.
![image_name](https://github.com/krystinmckee/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png) 

### Challenges and Difficulties Encountered
During this analysis, the primary challenge encountered was determining what criteria constitutes a "similar" campaign to Louise's. It is important that the campaigns studied in this analysis be comparable to Louise's campaign for Fever since we are using the data as a point of direct comparison. This challenge is overcome by filtering the dataset down to reflect the notable characteristics of Louise's campaign. By filtering the subcategory to include only "plays," we ensure that campaigns for incomparable projects (such as theater construction projects) are not includec in our comparison. Filtering by country is also important because the tendency of individuals to support the performing arts may be completely different from country to country.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
An analysis of the outcomes of Kickstarter campaigns in the theater category based on their respective launch dates provides a few interesting insights:
There is a clear relationship between launch month and campaign outcome. The number of succesful campaigns steadily increases from January until May, then declines through the end of the year.
  1. Theater campaigns launched in the month of May proved most likely to succeed when compared to campaigns launched during other months. 
  2. Theater campaigns launched in the month of December had the highest likelihood of failure.

- What can you conclude about the Outcomes based on Goals?
  1. There is an inverse relationship between campaign goal and campaign outcome. As campaign goal increases, the percentage of successful campaigns decreases. Campaigns for "Plays" with goals set below $5000 were more likely to succeed that those with higher goals.

- What are some limitations of this dataset?
There are several limitations of this dataset.
  1. While the dataset as a whole includes thousands of entries, the number of campaigns included in the dataset which could be considered "similar" to Louise's is limited. All in all, there are 673 completed campaigns in the US which fall into the "Plays" subcategory. This is a relatively small amount of data to analyze in comparison, making it more difficult to find strong trends or insights.
  2. The age of the dataset is also a limitation. The most recent data included in our sample is from 2017. Between the overall improvement of computer literacy and the fast-growing popularity of crowdfunding sites like Kickstarter, it is possible that a change in donor behavior would be seen in data from recent years.

- What are some other possible tables and/or graphs that we could create?
  1. By creating a graph to show campaign outcomes based on the overall duration of the campaign (in days), we could determine whether there is a relationship between the amount of time that a campaign is active and the likelihood of success. Perhaps a recommendation could be made on the minimum number of days a campaign should remain active in order to increase the chances of meeting the goal.
  2. Another graph could be made to show outcomes based on the average donation amount. Understanding this relationship could help inform future fundraising strategies - is it better to seek small donations from a broader audience, or large gifts from a select group of donors?
