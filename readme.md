# 2019 Ford GoBike System Data Exploration and Visualization
## by (Abdalla Elshiekh)


## Ford GoBike System

> The Ford GoBike's trip data for public containing approx. 2506983 bike rides that happen in 2019 in the San Francisco Bay Area. The dataset contained features about:
    1- trip duration: start/end time, how long the trip took in seconds
    2- stations: start/end station, name, geolocation (latitude/longitude)
    3- customer data : user type 
    4- rented bikes: bike id
    The dataset was further enhanced with features that I may find neccessary to perform interesting analysis:
    rental time: month, day, hour of the day, weekday (both for start and end date)

> I noticed rental_access_method column has high NAN values so i decided to not implement it in analysis so i will drop it then change the data type for start and end time to be Timestamps , also set user type and bike_share_for_all_trip to category.set bike id, start_station_id, end_station_id to object , It's time of timing ( extract start time month name , extract start time month number , extract start time weekdays , extract start time day , extract start time hour. 


## Summary of Findings

> I see Duration distribution after i performed transformation on second_duration variable which results the most common duration is about 10 mins.
> Subscribers in 2019 make 80.6% of trips and Customers 19.4%
>There is a difference in the trip duration between customers and subscribers. Customers trips are usually longer than for subscribers

## Key Insights for Presentation

> Distribution of Trip Durations:
In december the performance for subscribers is near from the performance for customers ,the lowest in subscribers and highest in customers .
> Distribution of Bike Share for all Trip:
When a user using bike for all trip get his distination faster than using more than one bike.