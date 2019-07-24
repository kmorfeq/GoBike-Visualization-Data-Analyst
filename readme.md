# (Ford GoBike System Data Exploration)
## by (Khaled Morfeq)


## Dataset

> This document explores a dataset containing duration_sec and attributes for approximately 519700 bike trip starting from 28th of July 2017 until the end of 2017.
The dataset can be found in the repository: [https://s3.amazonaws.com/baywheels-data/2017-fordgobike-tripdata.csv].


## Summary of Findings

> In the exploration, I found that there was no relationship between the duration of a trip and type, gender or age of the users. 
But in the other hand, there is strong relationship between the number of trips and type, gender and age of users. Also, Day of Week and the hours have a strong relationship. Weekend days have half the number of the trips comparing to workweek trips. The start and end of working-hours have the most number of trips and # of hours.



## Key Insights for Presentation

> For the presentation, first I focused on number of trips per hour of the day. After that, I plotted the distribution of Trips Per User Type during the period of the study and that shows a strong relationship between user types and number of trips where customers have took more trips than members.
Afterwards, I use the violin plots of duration_min across Day of Week. And after that, and stripplot plots of duration_min across Day of Week per user_type. Both plots indecate that there is no relationship between Day of Week and duration of trips
