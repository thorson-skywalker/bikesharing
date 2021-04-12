# bikesharing

## Purpose

The purpose of this project was to analyze NYC Citibike data and determine how to make the same program viable in Des Moines, Iowa. We wanted to add the 

## Results

Visual displays of the analysis can be found on the public Tableau workbook LTerrell_CitiBike_Challenge at the link below.
[Link to Dashboard](https://public.tableau.com/profile/luke1056#!/vizhome/LTerrell_CitiBike_Challenge/CitibikeAnalysis?publish=yes)

Our analysis looked at seven key areas of data that would help make the Citibike model transferable to Des Moines.

First, we looked at the most popular starting stations in NYC in an effort to determine what trends we could find in the most popular locations. To do this we used the longitude and latitude information for the start station ids to map them on NYC. We then adjusted the size and color of each station's symbol based on the number of times it appears in the data under the "starting_station_id" column in the CSV file. The data seems to indicate that the more populated and tourist centered areas seem to have the most traffic for starting stations.

Second, we pulled followed the same process for the End Station ids. We needed to see if the bikes were being used to get out of these areas, or if the bikes were being shuffled within the areas that were popular for starts as well. The data indactes that the most popular end stations are in the same areas as the start stations, suggesting that the bikes tend to stay in the same areas.

Third, We wanted to look at the typical checkout times. From this information we can also see how far the bikes will typically go. It appears a large majority of trips are from 4-8 minutes long. Again, helping us understand how far the bikes typically go.

Fourth, we broke down those trip times by gender to determine the demographics of the users for Citibike. This will help us determine who will be our target market. In this graph, we can see the vast majority of users are men. 

Fifth, we created a heatmap to determine the times of day most people used the bikes in NYC. This data gives us an idea of what time of day the bikes are most popular, and a general idea of what the usage trends are, how many bikes need to be available during those time periods, and potentially give us some insight into the reasons most people use the bikes. In this case, the data suggests the most popular times for the bikes to be used are from 8am - 9am and 5pm - 7am on weekdays, suggesting that commuters are the heaviest users of the bikes.

Sixth, we break down the data from the previous heatmap by gender. We can use this infomation to again establish our demographic base, which again indicates males are using the Citibike's significantly more than women.

And finally, our last graph takes the information from the last graph and breaks it down further into usertypes. This helps us further determine the type of user base that we will be expecting our primary revenue from. The data shows that the male subscribers are the primary source of revenue for Citibike for commuting to and from work.

## Summary

The data tells a clear story about the user base for Citibike. The primary users, and thus the primary income drivers, are men commuting to and from work during the week on a subscription for trips that are typically under 10 min long. This is important information to have, as it helps us to determine what market we should be targeting in Des Moines and also the research needed to be conducted to determine if a Citibike like product would even be viable. Two other visualizations and anaylsis I think would be beneficial to this project would be to get a breakdown on the amount of repair work needed on the bikes per mile. This would help determine the cost/benefit analysis of operating a similar business in Des Moines, and what the costs would be over time. Second, I would like to see an analysis of the age of usertypes. This information would again help us specify the demographic that would need to be targeted for the rollout in Des Moines.