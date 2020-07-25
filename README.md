# Kickstarting with Excel 

## 1. Overview of Project

### Purpose 

- We are performing an analysis on Kickstarter data to help Louise determine if there are specific factors that help make Kickstarter campaigns successful. More specifically we are looking at theater/play category and the relationship between fundraising goals and launch date over the years to determine if they have a significant effect on the likelihood of success for Louise's Kickstarter.

## 2. Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date

- Used Kickstarter data from 2009 to 2017 to create pivot table looking at Theater Kickstarters and organized the data based on outcomes (successful, failed, canceled) by month and created line graph located here: ![Theater Outcomes vs Launch](/Resources/Theater_Outcomes_vs_Launch.png).  

### Analysis of Outcomes Based on Goals 

- Used Kickstarter data from 2009 to 2017 to create a table looking at Plays Kickstarters and organized the data based on the outcomes (successful, failed, canceled) and grouped them by different goal levels. A line graph showing this data can be found here: ![Outcomes vs Goals](/Resources/Outcomes vs Goals.png). 

### Challenges and Difficulties Encountered 

- For the analysis of Outcomes based on launch date, one could face difficulty choosing the correct date grouping format. They may look by quarter and not by month leading to a misdiagnosis. If they looked by quarter they would of seen the 2nd quarter as the most successful but there are significantly more successful campaigns in May and June then April. To correct this, one would need to look at the field settings and make sure correct date format is selected as well as the dates not being grouped. 

- For the analysis of outcomes based on goals there may be a challenge for users trying to recreate this data as it could be tricky ensuring the COUNTIFS formulas are pulling the correct data. You can check this by making sure the total outcome count for successful, failed, canceled are equal to the total count once you filter the raw data by the same parameters and comparing the total count, which in this case is 1047 for both. 

## 3. Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Historically, from 2009 to 2017, May saw the most successful theater Kickstarter campaigns with a total of 111 successful campaigns, followed by June which had a total of 100. So I would recommend launching the campaign in May, and no latter than June.  

- What can you conclude about the Outcomes based on Goals?

The higher the goal target, the less likely you are to succeed. When asking for less than 5,000 the campaign has about a 3/4 chance of succeeding vs larger amounts which really just has a 50/50 chance. 

- What are some limitations of this dataset?

The biggest limitation I see is that this data doesn't show what each campaign did in terms of marketing nor list incentives they offered for those contributions. Each campaign would of provided images, videos and different incentives for different contribution levels. All of these could have had a significant impact. So next steps might be to focus on the successful campaigns to see if there is a common pattern of marketing/incentives they are doing to succeed. Additionally, you may want to look at other sources to see if they advertised there campaigns other ways, whether it be news articles, blog posts or other sources. This data would allow Louise to know what marketing efforts she needs to take on to reach her target goal.  

Additionally I would want to see the theater/play categories broken up by genre. Comedy and drama might have been relatively more successful than horror or other subjects. This can inform how to appeal to the audience in the descriptions and visuals. 

I would want to point out that while there appears to be greater success in the $35,000 to the $45,000 range, there have only been 9 such campaigns over the years compared to 720 campaigns asking for less than $5,000. So this larger range doesn't have enough data for me to confidently say that you have a greater chance of success asking  between $35,000 and $45,000.

- What are some other possible tables and/or graphs that we could create?

You could look at the average donation of the successful campaigns by the different goal ranges. If there is a recurring amount, or a range, then you may know that creating a good incentive for people to contribute that amount will be more likely to help you succeed. Additionally, seeing if the length of the campaign has any impact on the success of the campaign. You would just take the creation date and deadline date and count the number of days between each one. Then see if there is any relationship between length and success by different goal ranges and month of the year.
