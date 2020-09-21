# An Analysis of Kickstarter Campaigns
---
---
## Overview of Project
---
Louise, an up-and-coming playwright, has asked for assistance with crowdfunding her play "Fever", which has a budget of $10,000
---
### Purpose
---
Using data analysis tools available in Excel, this project attempts to provide Louise with information that will help her crowdfunding campaign be successful by analyzing:
- Outcomes Based on Launch Date
- Outcomes Based on Goals
---
## Analysis and Challenges
---
### Analysis of Outcomes Based on Launch Date
---
By using a pivot table, one can summarize the raw kickstarter data to focus on crowdfunding projects found in the Parent Category "theater" (which includes the Subcategory "plays") and filtered by years/months. Furthermore, one can break down which of these projects were successful, which failed, and which were canceled.
---
#### Results

Conclusion:

1. Based on the chart created from the data, one would likely come to the conclusion that April through August appear to be the best months to launch a theater related crowdfunding campaign with the most successful campaigns peaking in May. It is worth noting that February could be an outlier with above average successful campaigns.
2. While failed campaigns also peaked in May, October showed a noticeable uptick in failed campaigns on the chart from the prior month.

Limitations:

While the line chart appears to suggest that Louise should begin her crowdfunding campaign in the middle of year, preferably May, it is difficult to accept the reliability of this conclusion based on the analysis that was performed. The analysis does not consider the impact that each of the years (2009-2017) from which the data was drawn might have had on the months in question. There could have been a recession one year or perhaps May is more popular because donors have received their tax returns and are more willing to be charitable. There are too many variables not explored to reach a conclusive decision.

Furthermore, this analysis looks at the Parent Category as a whole and not the subcategories within. I would imagine Louise would be more concerned with how the subcategory "Plays" would perform if not grouped with the other 36 subcategories in "Theater" for the analysis. Even though 314 of the 604 projects (52%) that attempted funding for the time period were for "Plays", it is still not a fair representation.

'
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/70344787/93725246-83dbf100-fb7b-11ea-958b-940562610412.png)

Recommendations:

Before Louise makes a decision on **when** to begin crowdfunding her play, I would suggest that she looks at additional analyses such as:

- *Percentage* of successful projects for *plays* by year
- *Percentage* of successful projects for *plays* by month

By using percentage as opposed to total, one can better visualize the likelihood of a submitted project being successful. By first looking at the years and then months, one might determine a trend developing upwards or downwards. 

### Analysis of Outcomes Based on Goals
---
By using the COUNT(IFS) function, one can summarize the raw kickstarter data to focus on the success of crowdfunding projects based on the goal amount of money to be raised. The function can be used to pull specific data based on the criteria provided in the formula.
---
#### Results

Conclusion/Limitations:

Based on the chart created by the data, it appears that projects with lower funding goals are more likely to be successful and trend downward as the amount increases. At first glance, this conclusion might not look entirely accurate when you notice the success rate for projects with goals between 35000 and 44999 which could be outliers given that only 6 total projects fall in this range. 

**However**,I am purposely not using a currency sign for this observation because one of the flaws of this analysis has to do with currency translation as it is not taken into consideration. Projects may be funded in USD, GBP, EUR, etc... For this reason alone, I would suggest the data displayed in this chart cannot be relied upon.


![Outcomes_vs_Goals](https://user-images.githubusercontent.com/70344787/93727404-fa332000-fb88-11ea-86b9-548d405a9720.png)

Recommendations:

Even though the chart suggests that Louise's project has a better than average chance of being fully funded, this chart should not provide Louise with any comfort. Instead, I would recommend the folling changes:

-
