# Kickstarting with Excel - An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends 

---
## Overview of Project
This is a classwork example in which "my friend" Louise is an up-and-coming playwright who will be starting a Kickstarter fundraiser campaign to help fund her play entitled *Fever*. This data analysis will help her track trends in similar past Kickstarter campaigns. 

### Purpose
We will analyze data from past Kickstarter campaigns that were started for theater projects to be able to see comparable campaign outcomes based on the campaign's launching date as well as outcomes based on the campaign fundraising goals. 

A campaign's outcome will be labeled as 'successful', 'failed', or 'canceled'. Campaigns were labeled as successful if the amount of money pledged surpassed the fundraising goal. They were labeled failed if the campaign did not have enough funds pledged to surpass the goal. Canceled campaigns were labeled as such if the campaign was shut down before the end date passed. 

---
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
From all of the Kickstarter data available, results were filtered to view only campaigns that were categorized as "theater" campaigns. 

Of all campaigns in the theater category, there was a 61% chance of success compared to a 39% chance of failure or cancellation. The largest amount of successful campaigns launched in May. The largest amount of failed campaigns launched in May, June, July, and October. In December, theater campaigns were almost just as likely to fail (47%) as they were to succeed (49%). 

![Theater Outcomes Based on Launch Date Graphic](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
From all of the Kickstarter data available, results were filtered to view only campaigns that were categorized as "theater" campaigns. They were then further filtered to view only theater campaigns that were subcategorized as "plays". 

Smaller goals were more successful on average. Over half of the play campaigns had a fundraising goal within the range of $1,000 to $4,999. This goal range had the most amount of projects and the most amount of successful campaigns with 388 successes. Due to having the most amount of projects within this range, it also had the most amount of projects failed, although all other goal ranges measured had a worse success to failure rate. 

![Outcomes Based on Fundraising Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
In this data set, there was a measure for the original fundraising goal, the total fundraising pledged, and percentage funded. There were some campaigns that had low goals and high amounts of funds pledged, which caused extreme data points to lie outside the bounds of the standard (1.5 * IQR) outlier equation. These points were not excluded from the dataset. 

Some campaigns also had large goals and large amounts of funds pledged. These data points would not be relevant to Louise since her goal will be significantly less than these samples. Campaigns with large goals or large amounts of funds pledged also had large average donation amounts. There could be several reasons for this average donation amount. Most of these data points were excluded from the categorized and subcategorized data. Any large goals were reflected in the 'Outcomes Based on Goals' sheet. 

---
## Results
Theater project outcomes based on launch date gave insight into what month Louise could start her Kickstarter campaign for her theater project. There is a significant increase in successful campaigns that launch in the months of March to July. May has the best success rate. 

Based on goals, Louise will need to be mindful of her fundraising goal to ensure her project succeeds. Louise believes she needs $12,000 to fund her play, but data shows that having a higher goal ($10,000 to $14,999) has only a 54% chance of success. Louise would be better off to set a fundraising goal within the $1,000 to $4,999 range which was shown to have a 73% succees rate.

This dataset had limitations as it related to Louise's project. There were some extreme data points that caused summary statistics to be skewed. There were a few Kickstarter campaigns that were currently live during the time the data was collected which caused us to filter those results out to get only completed data. We used filters to significantly limit the data to view only relevant results in the theater and play categories, but there are other categories that Louise could preview to learn more about fundraising for entertainment. 

Louise could look into the same data points using the theater/ musical category/ subcategory, or look at the film&video/ shorts categories. I believe these categories are similar enough to Louise's project that some additional launch date or goal information could be considered.

Louise could also examine campaign end dates and the length of campaigns to see what the optimal length of a campaign is according to the data. 
