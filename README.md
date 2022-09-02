# surfs_up
Analysis of weather data for the surf shop using python, sql lite and sqlalchemy

## Overview
The goal of this analysis is to create a basic statistical analysis of the temperatures on Oahu during the months of June and December. This is to help determine whether or not the surf and ice cream shop business is sustainable year-round. By creating a query that captures the temperatures specifically for the months of June and December, we can retrieve information such as average, maximum, and minimum temperatures.

## Results
### June Analysis
Based on the analysis, we can see that there are 1,700 observations for the months of June. This includes the years between 2010 and 2017. The average, minimum, and maximum temperatures are listed below. The low standard deviation implies a relatively small spread across the temperature observations. This makes sense, as Oahu weather does not seem to fluctuate significantly.

![](june_result.png)


### December Analysis
December, on the other hand, seems to only have 1,517 observation. This indicates that some of the dates are missing temperature recordings. However, this is already a large sample size, thus our analysis will still be relatively representative. From the charts, we can see that June and December are close in average, maximum, and minimum temperature. More importantly, the spread is about the same as the spread for the month of June.

![](dec_result.png)

## Summary

By comparing the statistic summary of the two months, we can conclude that temperature patterns remain steady throughout the whole year. Although temperatures may remain about the same throughout the year, precipitation may not and would also have a significant impact of the business's sustainability. Doing a statistically summary of the precipitation patterns during the months of June and December will give us a better picture of the overall weather pattern.

Another query that can be created to help us further our analysis is comparing the most active stations to the weather patterns. This can help us narrow down the best location by giving us the most popular station combined with the most stable weather patterns.

