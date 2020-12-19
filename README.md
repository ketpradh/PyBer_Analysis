# PyBer_Analysis by Ketaki
## Overview
This project summarizes the Py-Ber data for the user by city type using Pandas and Python(Matplotlib). There are three city types in the given dataset - Rural, Urban and Suburban.
- The first part of the project summarizes the data by city type in a DataFrame comprising of the total number of rides, total number of drivers, total fares, average fare by ride and average fare by driver. This is achieved using the grouby(), sum() and count() functions.
- The second part plots a multi-line graph that shows the total weekly fares for each city type. This is achieved using the pivot() and resample() functions of Pandas.
- We then highlight the diferences in data for each city type that can be used to make strategic decisions by the Py-Ber team.
## Results
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.
From the summary table below, we can find that:
![Py-Ber Summary by City Type](https://github.com/ketpradh/PyBer_Analysis/blob/main/Summary%20by%20city%20type.PNG)
- Urban cities have more number of rides than the other two city types, more than twice than Suburban cities and thirteen times higher than rural cities. 
- Urban cities have more number of drivers than the other two city types. Suburban comes second and rural third. The driver count in the urban cities is almost 5 times to that of suburban cities and 30 times to that of rural cities. More drivers are employed by Py-Ber in urban cities than others.
- Urban cities have the highest total fares than the othe two city types. The total fares in urban cities is twice the total fares in the Suburban cities and nine times the total fares in the rural cities. 
- However, in terms of average fare per ride, rural cities with the highest average fare per ride, followed by suburban and then the Urban cities. The difference however is not very high and is approximately in the range of (~$4 - $6) between the three city types.
- The Average fare per Driver is the highest in Rural cities, followed by Suburban and the least in Urban cities. The Average fare per Driver in rural cities is three times higher than that in urban cities and around 1.4 times than suburban cities.

- From the multi-line graph below, we find that the total weekly fares is highest in Urban cities, followed by Suburban cities and least in Rural cities.
![Total Weekly Fares by City type](analysis/PyBer_fare_summary.png)
## Summary
- The results of the total number of rides,total number of drivers and total fares by city type show us that there is a lot of demand for Py-Ber rides in the Urban cities than rural or suburban cities. Hence, more revenue(~63%) comes from Urban cities. **Any improvements or new rollouts must be send out to this city type first**.
- We can however find that **the number of drivers in the urban cities is higher than the number of rides.** This means that some of the drivers are not getting enough Business. **This is also reflected in the Average fare per Driver values which is lowest for urban cities, where there is more supply(drivers) than demand(rides).**  
So, these drivers can be useful in the other two city types where is more demand for drivers.
### Increase the number of drivers in rural and suburban cities
The Average fare per ride is the highest in the rural cities which might be because the price of a ride is higher because of more demand and less supply(surge pricing). (Or people take rides for longer distances/duration in the rural cities). This surge pricing  might be a deterrent for residents in rural cities(and likeise in suburban cities) and a factor for the lower number of rides in the rural cities. 
