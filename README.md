# Capstone---Case-Study-1
## Google Data Analytics Certificate Course


### Introduction
The following R code was done on RStudio in order to clean, analyze and visualize a summary dataset; created for my capstone project as part of the "Google Data Analytics Certificate" Course. The case study for my capstone project is to understand different types of bike-sharing user (members & casual users) patterns in Chicago, US by Cyclists company.

This data source is from Cyclistic’s historical trip data: Index of bucket "divvy-tripdata" (https://divvy-tripdata.s3.amazonaws.com/index.html). Raw data was taken from the past 12 months (1year) – from Nov-2020 to Oct-2021. The packages utilised for this analysis were: tidyverse, lubridate and ggplot2

*Note: Cyclistic is a fictional company for the purpose of this case study. The above-mentioned dataset is made available by Motivate International Inc, under this licence (https://www.divvybikes.com/data-license-agreement)



### Assumptions 
The assumptions made was any ride_length of less than 1minute were recorded wrongly, as it does not make sense to ride for less than a minute from one destination to another. No (or small insignificant amount) of longitudinal and lateral coordinates were displaced for ride_length of less than 1minute. Hence, any ride_length less than 1minute were considered invalid data and was deleted


### Analysis
The result of the analysis between casual users and annual members were cleaned and tabulated as below. The main 2 parameters to study their patterns are the number_of_rides and average_ride_duration between both types of users; for each day of the week throughout 1 year.

	| member_casual |	weekday |	number_of_rides	| average_duration |
  | ------------- | ------- | --------------- | ---------------- |
  |   casual		  |   Sun		|  181293		      |  3581.405388     |
  
2	casual		Mon		103296		3372.286923
3	casual		Tue		90510	      	3596.359949
4	casual		Wed		92457	      	3718.661897
5	casual		Thu		102679		3682.984671
6	casual		Fri		122404		3773.835112
7	casual		Sat		209543		3331.913841
8	member		Sun		267965		919.9746161
9	member		Mon		472196		842.5725694
10	member		Tue		508445		826.142747
11	member		Wed		500329		823.9996442
12	member		Thu		484177		823.9278033
13	member		Fri		452790		824.5305064
14	member		Sat		287958		968.933723


### Visualizations
Total Number of Rides of Casual vs Members
![Total no. of rides](https://github.com/justin950717/Capstone-Project-1/blob/master/Visualizations/total_no_of_rides.png)


Average Ride Duration of Casual vs Members
![Average Ride Duration](https://github.com/justin950717/Capstone-Project-1/blob/master/Visualizations/average_ride_duration.png)

Summary Visualization
![Summary Visualization](https://github.com/justin950717/Capstone-Project-1/blob/master/Visualizations/Summary%20Results.png)




