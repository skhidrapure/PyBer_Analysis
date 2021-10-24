# PyBer_Analysis

## # Overview of the analysis
Perfoming analysis & creating visualizaton using the ride share data to help improve access to rideshare services and determine afoordability for underserved neighnorhoods. To perform this analysis we'll be using Python skills and knowledge of Pandas, then we'll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, we'll be submitting a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.


This analysis is done in three parts:


1. Creating a ride-sharing summary DataFrame by city type

2. A multiple-line chart of total fares for each city type

3. A written report for the PyBer analysis (README.md)

## Results

The analysis was done to provide Pyber to help improve access to ride-sharing services & determine affordability for underserved neighborhoods.

The first part, the analysis was done using pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, we got the total number of rides, total number of drivers, and the total fares for each city type. 

Then, calculated the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.

The results of the dataframe are as shown below:

![](Analysis/ride_share_Summary_df_by_city)

The second part we created a multiple line chart of the total fares for each city type.

The results graph is as shown below:
![](Analysis/total_fares_for_each_city_type)
![](Analysis/PyBer_fare_summary)


Observations:

From the ride-sharing summary DataFrame by city type it is seen in terms of cost that, urban city had the total fares of about $39854.38 where the avg fare per driver is $0.67 for an avg fare per ride of $24.53. When we compare this to rural city type the avg fare per ride is $10 more than the urban city & also the avg fare per drive for rural is more than the suburban which is $2.26 & urban which is $0.67.

The multiple line chart of Total fares for the city type further supports the ride-sharing summary dataframe. The line graph shows how the urban, suburban & rural city type performed between January 2091 to April 2019. The yellow line shows us the total fares for urban cities totaled from around $1600 to $2300. The orange line shows the total fares for suburban cities totaled from around $700 to $1300 from the start to end of during this time. When we observe the blue line which represents the rural cities total fare which totaled from $300 from beginning to end during the same time period. 

The other observation from the multiple line graph is that there were similar peaks times in all three cities. The peak for total fares among the urban, suburban & rural occurred towards the end of February 2019.
