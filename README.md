# Pyber_Analysis
## Overview of the Analysis

The purpose of this analysis is to take ridesharing data for a set of cities and analyze the statistics for the city set grouped by rural, suburban, and urban types of cities over a period of time. This data was then used to create a summary dataframe and a line chart to visually display the results of the analysis. 

## Results

### Overall Dataframe

The dataframe compiling the information for each city type is as follows:
![image](https://user-images.githubusercontent.com/92831138/146031783-b70cf77b-efb4-4e2d-8dc8-315f90eada9e.png)

As can be seen, as the type of city changes from rural to suburban to urban the number of rides and drivers increases. Naturally, this also results in a larger total amount of fares for urban cities than the other types. Conversely, this means that as cities move from urban to suburban to rural the average fare per ride and driver increase. Most notably, the average fare per driver in rural cities is almost $40 higher than it is in urban cities due to the much smaller number of available drivers. 

### Line Graph for Four Month Span

The following line graph is a compilation of the data for a period between 01/01/19 and 04/28/19:
![image](https://user-images.githubusercontent.com/92831138/146596159-6c291a04-bfa1-4f55-bc1f-e6d93b88ee0d.png)

The graph visually displays the same conclusions that can be reached from the earlier dataframe. Urban cities have higher fare totals than suburban cities, which in turn have a higher total than rural cities. There are small changes to each line over time, but nothing of such a magnitude that it causes any line to intersect with another for the observed period. At least from this data it can be determined that time of year impacts the amount of fares in a given city but that on the whole the cities that are urban will have a higher total fare amount. 

## Summary

Based on the results several recommendations can be made to the CEO for addressing disparities between the types of cities.

1. The large disparity in average fare per driver as cities move from being urban to rural is caused at least in part due to the overabundance of drivers in urban cities and the scarcity of drivers in rural cities. To combat this more drivers could be hired in rural cities, however it is debatable if this would be the best course of action. Doing so would cause a decrease in the profits of drivers in those areas and would not necessarily be in their best interest. 
2. The larger total fares for urban cities compared to suburban and rural cities is due to the larger total number of rides given in those cities. A way to address this would be to increase advertising in more rural and suburban cities to increase the number of users requesting rides from the service.
3. The average fare is lower as cities become more urban, being almost $10 less than the average fare in rural cities. This could be due to factors not shown in the dataset, such as length of rides. This could be addressed by increasing the fare cost in urban cities, but this could potentially result in a loss of customers to competitors. 
