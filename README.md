# PyBer_Analysis
## Overview of the analysis
We will do analysis on Pybar a python based ride sharing app.The purpose of this project is to do exploratory analysis of there data and to create  various visualization chart with the help of python graphing library Matplotlib.
The primary things to be done is.

1.To show the relationship between different types of cities and total number of drivers and riders.

2.To show the percentage of total fare by riders and drivers by the type of cities.
  This analysis will help Pyber improve access about there ride sharing services and determine affordability for underserved neighborhoods





## Results
First two dataset is merged ride_data.csv and city_data.csv based on city.
![](Dataframe_city_ride.png?raw=true)
## Then total rides based on city type is calculated.
### Rural        125
### Suburban     625
### Urban        1625
![](Total_ride.png?raw=true)
## Then total number of drivers based on each city type is calculated.
### Rural        78
### Suburban     490
### Urban        2405
![](Total_driver.png?raw=true)
## Then the total amount of fare is calculated based on city type.
### Rural        4327.93
### Suburban    19356.33
### Urban       39854.38
![](Amt_fare_city_type.png?raw=true)
## Then average fare Per Ride is calculated
### Rural       34.623440
### Suburban    30.970128
### Urban       24.525772
![](Avg_fare_per_ride.png?raw=true)
## Then average fare Per Driver is calculated

### Rural       55.486282
### Suburban    39.502714
### Urban       16.571468
![](Avg_fare_per_driver.png?raw=true)

## Total Weekly fare for each city types is calculated
![](Resample.png?raw=true)

## A new dataframe is created using "resample()" function by week 'W' and get the sum of fare for each week
![](Resample.png?raw=true)
## Finally using the object-oriented interface method,  we plot the resample DataFrame using the df.plot() function
![](Pybar_fare_summary.png?raw=true)


## Summary 
1.The analysis shows that the total fare for each city type is very low at the begining of the year Jan and Feb ,so in order to increase the business there 
should be some incentives added so that more ride takes place.

2.The average fare per ride is very high in rural area $34.62,and the total drivers is less then the total rides take place in rural area,so inorder to increase
 the business in rural area more drivers need to be recruited.
 
3.Again in the urban area the total fare per driver is comparatively low $16.57 ,as we can see that the total number of drivers in urban is quite high 2405 and total rides is 1625,in order to increase the total fare per driver in urban area the total number of drivers should be reduce inorder to increase the average fare per driver.

