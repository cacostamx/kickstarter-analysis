# Kickstarter Campaign Analysis

## Overview of Project

Louise launched a fundraising campaign on Kickstarter for her ***Fever*** play which was almost successful in getting to the goal in short period of time.

### Purpose

This is an analysis of other Kickstarter campaings to determine how well they performed based on their launch dates and goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

From the Kickstarter database we filtered outcomes for Theatre campaigns and their outcomes: *Successful*, *Failed* and *Canceled*.

![Outcomes by Launch Date](/resources/Theater_Outcomes_vs_Launch.png)

Out of 1,369 theatre campaigns, 839 were *Successful*, 493 *Failed* and only 37 where *Canceled*.

The most active months for launching theatre campaigns have been may through july, which account for 33.4% of historical campaigns, and also have the most successful campaigns relative to the total in each month, 67%, 65% and 63% respectively.

Also, if we sort the data by year we find that 2014 to 2016 are the years with more campaigns.

| Years | Successful | Failed | Canceled | Total |
|-------|------------|--------|----------|-------|
| 2010  | 3          |        |          | 3     |
| 2011  | 4          |        |          | 4     |
| 2012  | 8          |        |          | 8     |
| 2013  | 11         |        |          | 11    |
| 2014  | 241        | 152    | 10       | 403   |
| 2015  | 304        | 202    | 12       | 518   |
| 2016  | 249        | 130    | 12       | 391   |
| 2017  | 19         | 9      | 3        | 31    |
|-------|------------|--------|----------|-------|
| Total | 839        | 493    | 37       | 1369  |

It is also to be noted, that the campaigns from 2010 to 2012, although they were few, all were successful, and for the coming years successful campaigns accounted for a mean of 61%.

### Analysis of Outcomes Based on Goals

Now, we filtered the data for *Plays* subcategory and by *Goal* ranges, as shown in the next graph.

![Outcomes Based on Goals](/resources/Outcomes_vs_Goals.png)

Up to $20,000 goals, there are more successful campaigns. However, it is reverted from $20,000 to $35,000, and then again from $35,000 to $45,000. Finally, above $45,000 almost are failed campaigns.

For the *"plays"* subcategory, there were 66% of successful campaigns. Around 76% of successful campaigns goals were less than $5,000. In that in that same range, there were 54% of failed campaigns.

Another metric is to count for the backers in each range for successful campaigns. Data indicates that as goals are larger, backers need to increase.  For sucessful plays with goals over $10,000 the number of backers were over 120 in average.

Finally, if we analyze the percentage funded for successful *"plays"* campaigns, the average is 128% for all successful campaigns; however, for goals less than $1,000 the average percentage funded is 189%.

### Challenges and Difficulties Encountered

When analyzing data from Kickstarter campaigns, we can establish some tendencies, but there is not enough data to describe those behaviors.  For example, we can't tell why are some months better than others.

If we want to further analyze details, like the type of plays, it is not easy to create a data column with sub-subcategories, such as comedy, drama, etc.

Managing dates could also be a limitation if analyts are not familiar with Unix timestamps or how to convert them to more readable formats.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

First of all, it is clear that for *"theatre"* campaigns have been 61% successful, so it is a category that kickstart backers like.

Historically, we found that may and june have yielded the most successful campaigns, with 67% and 65%, respectively.  Additionally, it seems that december is not the best month to launch a campaign, as there is a 50/50 chance of being a successful or a failed campaign.

- What can you conclude about the Outcomes based on Goals?

First of all, data shows that 51% of all *"plays"* campaigns are in the range from $1,000 to $4,999, and 73% of these campaigns were successful.  Actually, the median of goals for **successful** US campaigns in this subcategory is $3,000, with lower and upper quartiles of $1,500 and $5,000, respectively.

Although, it is not clear whether campaings with goals in low ranges will be more successful than those in the high range, data shows that historically there were more successful campaings with goals less than $5,000.

Also, as the goal increases, the number of backers needed increases as well, which could affect the pledge if the time span of the campaign is not enough.  It may also be true, that backers prefere to pledge in campaigns that require less investment.

- What are some limitations of this dataset?

One limitation of the dataset is that it is really more country specific to the US with 74% of total campaigns, followed by GB with 15%, so it is difficult to extrapolate to other countries as backers are cultural influenced.

Apparently, the dataset has information up to march or april of 2017, because the maximum ending date is in may 2017, making this particular year to have very few campaigns compared to previous years.

It would be a good addition to include backers' age and sex to have some demographics analyses.

There could also be more sub-subcategories to be more specific in our analyses. In the case of theatre plays, we could have types of plays, such as comedies, tragedy, historical, etc.


- What are some other possible tables and/or graphs that we could create?

Comparing outcomes and goals for both the US and GB could give us some insights about difference of backers in both countries, which could make a difference in the analysis.

We can make amount pledged tables for goal ranges to show if backers pledges are higher as goals increase.  For these, we should either convert all amounts to one given currency or analyze it by country.

I would graph the duration of both successful and failed campaigns for different categories to see if there is a common denominator.

Finally, there should be graph of outcomes based on *spotlight* and *staff_backed* campaigns to analyze all possibilities from the dataset.
