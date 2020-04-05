# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends.  As discussed, the task was to assess the Kickstarter data provided to determine if the length of a campaign contributes to its ultimate success or failure.

### Challenge

What contributes to the success of Kickstarter Campaigns?
1)	Size of the goal.
2)	Month the campaign started
3)	Location of the campaign
4)	Length of the campaign 
5)	Type of campaign

In the study performed to date, I will focus on two factors: 1) Size of the goal and 2) Month the campaign started.

### The Month the Campaign Started

!["Outcomes Based on Launch Date"](https://github.com/Duegan24/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Launch%20Date.png)

To create the above graph, I filtered the data provided by the category Theater because I felt it was critical to have enough of a sample size to be able to assess if the month that the campaign started would have an impact on its success.  This assumes that all subcategories of the category Theater are likely to be equally impacted by the start time.

Based on the above graph, the starting month of May is when most successful campaigns are started.  For the next four months the likelihood of a successful campaign declines steadily.  December is demonstrated to be the lowest like month for a successful campaign. 

### Size of the Goal

!["Parent Category Outcomes"](https://github.com/Duegan24/kickstarter-analysis/blob/master/Outcomes%20Based%20on%20Goals.png)

To create the above graph, I filtered the data by the campaign subcategory by Plays, which is type of campaign you are most interested in.  Based on some initial analysis ahead of time, it was clear that the rate of success is dependent on the type of campaign and so it was important to focus on the type of campaign that you were most interested in.

Based on the graph above, campaigns with goals between $1,000 – $4,999 have the greatest chance for success and that those with $5,000 – $14,999 have the next most likely for success.  Outside that core range, success varies considerably with many at or below 50%.


### Next Steps

Now that we understand the impact that the start time and goal size of the campaign, the next steps will be to take this analysis to the next step, evaluating the other three possible factors that could be influencing the success rate of the campaigns.  

It is important to note the limitations on the current data set and possible enhancements which could improve this analysis.   The dataset provided ends at 2017 and may not reflect the most current social trends; it would be beneficial to get a more current dataset, if possible.  In addition, the categories and subcategories focus on the method of that information is provided to an audience; however, it does not account for the genre of campaign.  It is likely that the success rate of some of the campaigns was due to the primary genre that was being presented; this would merit further study.
