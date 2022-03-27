# PyBer_Analysis
## Overview
  An analysis was performed on data from Pyber, a python based ride-sharing company, to determine trends in ride-sharing data by city type. The weekly fares for each city type were compared to determine any differences in the data by the type of city being analyzed.   
## Results
  To start the analysis, I first grouped the data by the count of rides, sum of drivers, and sum of weekly fares by the three types of cities: rural, suburban, and urban. I then divided the sum of the weekly fares for each city type by the count of rides and sum of drivers to determine the average fare amount per ride and the average fare amount per driver for each city type. A summary of this data can be seen below:
  
![This is an image](https://github.com/dsilvaggio/PyBer_Analysis/blob/main/Resources/Pyber_Summary.png)
  
  I then grouped the data again to create a new dataframe that showed the sum of the fares for each city type by the date the ride took place. I created a pivot table from this new dataframe to get the total fares for each city type by the date, and then created a new dateframe from this pivot table that only showed rides that occured from Janurary to April. I then resampled this dataframe to determine the sum of the fares by week for each city type between January and April. I then created a line graph fro this final DataFrame, which can be seen below:
  
![This is an image](https://github.com/dsilvaggio/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

From the above analysis I was able to see that:
  - Urban cities have the highest ride demand, as well as the highest amount of drivers.
  - Urban cities have the lowest price per ride.
  - Urban cities are the only type where the average fare per ride is more than the average fare per driver, as well as the only city where the total number of rides in less than the total number of drivers. 
  - The average price per ride and average price per driver are the most expensive in rural cities.
  - The total fare amount was low for Suburban and Rural cities in the month of march, but increased for urban cities.
  - The time of the year when all three city types saw an increase in total fare amount was the end of February. 
## Summary & Recommendations
Based on the above analysis, I would offer the following recommendations:
  1. Increase the amount of drivers in rural cities in order to lower the average price per ride that customers are paying. 
  2. Increase the price per ride in urban cities in order to ensure that drivers are making more income.
  3. Encourgage drivers from urban cities to take trips in suburban areas so that the demand in suburban areas is met, as well as lowering the supply in urban areas so that these drivers can make more income. 
