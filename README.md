# An Analysis of Kickstarter Campaigns
Overview:
This project focused on analyzing Kickstarter campaign data to determine if there were certain factors that made a campaign successful. The project also focused on the estimated fundraising goals needed based on a comparison to campaigns in the same category/subcategory.

---
## Analysis and challenges
I performed my analysis by looking for trends in the data of campaigns as a whole and my client's category of interest.
Questions I looked to answer during my analysis included:
* How successful was the Theater category as a whole in comparison to other parent categories?
* What did the outcomes of the Theater category and Plays subcategory look like?
* Is there an optimal time to launch a campaign?
* What were the outcomes based on the fundraising goals?
---
### Distribution of outcomes based on parent category and subcategory
---
Sheet PC1 displays the outcomes of parent categories. As a whole, it seems that the Theater category is a popular and generally successful category as reflected in the Parent Category Outcomes chart. 

![Parent Category Outcomes](https://github.com/Aleahkita/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes.png)

The data can then be narrowed down to show a similar graph of outcomes for campaigns in the US of which 525 successful outcomes out of 912.

![Parent Category Outcomes (US)](https://github.com/Aleahkita/kickstarter-analysis/blob/main/Parent%20Category%20Outcomes%20(US).png)

---
### Optimal time to launch a campaign
When analyzing outcomes based on launch date, it seems that most successful campaigns were launched in May (the trendline then tapers off toward the end of the year). We can also narrow the parent category down to Theater, showing a similar trend.

![Outcomes Based on Launch Date](https://github.com/Aleahkita/kickstarter-analysis/blob/main/Outcomes%20Based%20on%20Launch%20Date%20(2).png)

---
### Outcomes based on fundraising goals
Looking at the percentage of successful outcomes, there is a downward trend as the fundraising goal increased (with exception to the 35,000 to 44,999 range). The trend of the failed outcomes shows a mirrored image (with exception to the same range) with an upward trend as the goal amount increased. 

![Outcomes Based on Fundraising Goals](https://github.com/Aleahkita/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

---
### Additional research on musicals in Great Britain
Analysis on musicals in Great Britain are visualized using a box plot (Box Plot (GB Musicals)) to get a rough idea of funding needed. The estimated fundraising goal is quite higher than outlier of the pledged amount.

---
### Challenges
Some challenges I encountered while analyzing Kickstarter data were whether to look for trends in the dataset as a whole to draw conclusions or to narrow my search down to the specific parent/subcategory of my client's interest. To overcome this I separated elements of the dataset and made them filterable by both criteria; this would give the client specific information on their category as well as allow them to compare between others.

---
## Results
Based on the theater outcomes by launch date, I can conclude that the ideal month to launch a campaign is in May. In addition to this, I can also conclude that after May there is a clear downward trend of successful outcomes through the remainder of the year. This means that the chances of having a successful campaign outcome decreases after the month of May through December.

When looking at the outcomes based on goals, the highest percentage of successful outcomes were for campaigns with a goal of less than $1,000. The higher the goal amount, the lower the percentage of successful outcomes. This is reinforced by the trend of the percentage of failed campaigns, showing that the lowest percentage of failed outcomes were for campaigns with a goal of less than $1,000. As the goal amount increased, there was a trend of higher percentages of failed campaigns.

Some limitations of the dataset were the range of data based on years and the source of the data. The range of data ends in 2017, we could add more recent data which might give insight into more current trends of successful/failed outcomes. The source of the data also limits our analysis because it is pulled from the platform Kickstarter. The client is interested in crowdfunding but doesn't specify which platform she intends to use. Different crowdfunding platforms could yield varrying outcome results based on the platform's structure, user base and features.

An additional table we could create would be one displaying the count of outcomes of categories over time in years. Using this we can look at our client's specific category and subcategory to see if there is consistency with successful campaigns.  We could then insert a line graph to see if there is a trend for successful/failed campaigns through the years to help visualize the results.
