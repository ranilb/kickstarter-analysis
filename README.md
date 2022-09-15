# An Analysis of Kickstarter Campaigns

## Overview of Project
Analyzing crowdfunding data to determine limitations and challenges of a successful campaign. 

### Purpose
Louise, a playwriter, has started a fundraising campaign and now she wants to know “how different campaigns fared in relation to their launch dates and their funding goals." Therefore, in this work, we search for the connections between successful campaigns and their launch dates with funding goals.  

## Analysis and Challenges
This fundraising analysis with available historical data (KickStarter worksheet) is completed in two steps. First we consider the outcomes based on Launch date (month of the year) and then we focus on the outcomes based on Goals of each campaign.

### Analysis of Outcomes Based on Launch Date
In this approach, first the launch year of each campaign was extracted from the KickStarter worksheet. Then a pivot table is created by filtering Parent Category and Years. The rows represent months of the year and the columns represent "Successful", "Canceled" and "Failed" campaigns. Please see below the resulting pivot table.

![image](https://user-images.githubusercontent.com/112113327/190472552-48d019c7-a69c-40ee-ad3f-7cf8716903e5.png)

The line graph that shows the campaign status aginst the month is shown below.

![image](https://user-images.githubusercontent.com/112113327/190472992-4480ab68-2884-4283-bd06-7a6b4aaa66eb.png)


### Analysis of Outcomes Based on Goals
As the second step of this analysis, percentages of three outcomes: Successful, Failed and Canceled were computed based on goals of campaigns. There, the goal amount was divided into 12 different intervals starting from "Less than $1000" to "$50,000 or more" as shown in the following table.

![image](https://user-images.githubusercontent.com/112113327/190473337-5e4cc8e3-b7bf-4f7b-a760-b6e12beccb83.png)

The following line graph shows the percentages of "Successful", "Failed" and "Canceled" campaigns of "play" subcategory.

![image](https://user-images.githubusercontent.com/112113327/190473836-09dd77ce-1d16-497d-b57d-ebc6189280b0.png)



### Challenges and Difficulties Encountered
In the second step of this analysis, the goals of campaigns were divided into 12 different intervals. 
However, these intervals are not the same in length. This would be affected to the conclusions.  


## Results
As seen in the graph of "Outcomes of Theater Campaign Based on Launch Date", many campaign launched between May and September are more successful. Also, a smaller number of campaigns were launched between November to January compared to the other months. Therefore, it would be a great idea to launch campaigns between May and September and to avoid launching campaigns during the months of November, December and January. 

Also, according to the "Outcomes based on Goals" results, it can be observed that the campaigns are more successful when the goal is less than $10,000. Therefore, it would be great if the goal of the campaign limits to $10,000 or less.

In the second step of this analysis, the goals of campaigns were divided into 12 different intervals. 
However, if the first and second intervals are combined, the length is $4,999 and about 70% campaigns belong to that combined interval and only 30% belongs to the rest of the intervals. That implies this data set is _left skewed_ and would be affected to the conclusions.  


In addition to the above analysis, it would have been helpful if campaign length was graphed against the successful, canceled and failed campaigns. In that way, the campaigners can decide whether it would be a short campaign or a long campaign and prepare ahead of the time.

