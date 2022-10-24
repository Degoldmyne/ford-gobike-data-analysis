# Data Exploration for the Ford Gobike System
## By Leleji Godwin Lucky


## Dataset
The dataset is the Ford Gobike dataset.


Ford GoBike is a bike sharing system that is managed by Motivate. They are electric bikes that makes transportation convenient, healthy, affordable and a fun experience.

Motivate runs a fleet of specially designed electric bikes that are locked into a network of docking stations. Bikes can be unlocked from one station and returned to any other station in the system. People use bike share to commute to work or school, run errands, get to appointments, and more.

## Details of  the Dataset
The ford Gobike dataset initially contains 183412 rows and 16 columns. Some of the columns that were irrelevant to the current analysis were removed and new features were engineered as necessary.

After the initial wrangling, the dataset now has 167,424 enteries with 9 columns/variables. Below is a list of the variables that were used for this analysis.

1. start_station_name (string): The name of the start station.
2. end_station_name (string): The name of the end station.
3. user_type (categorical): The type of user - could be Customer or Subscriber.
4. member_gender (string): Gender of the user.
5. bike_share_for_all_trip (categorical): Boolean value indicating if user is enrolled in Bike for All program.
6. start_weekday (string): Day of the week when bike was hired.
7. time_of_day (string): Time of the day when bike was hired.
8. riders_age (int): The age of the Rider.
9. ride_duration (float): The duration in minutes that bike was hired.

The goal of the analysis was to find the factors that increases the ride duration. Consequently, the dependent variable was ride_duration and the other variables in the dataset became the independent variables.


## Summary of Findings

> Some trips are short and last for about a minute, some are very long lasting more than 1400 minutes. The majority of the trips in the dataset are between 4 to 30 minutes. Short trips are mostly trips that involves Subscribers. Subscribers typically use the service for commutting purposes. The mean ride duration for Subscribers is around 10 minutes. Customers have more than 2x of that. Customers could represent Tourists or simply Recreational Cyclists or even those using the service for fun and exercise.

> Weekdays typically record the highest amount of trips with some days of the week recording over 32,000 trips. weekends on the other hand have low number of trip, sometimes fewer than 15,000. Subscribers use the service typically for commutting on weekdays. Our data shows that Customers use the service more on weekends. In addition, it is observed that the mean ride duration for females is higher than males for everyday of the week.

> The number of trips vary with time. Our data shows that for weekdays, 7am to 9am are rush hours as are 4pm to 7pm There a spike in the number of trips averaging about 40,000 to 45,000 trips at these periods. This point to the fact that majority of the users use the service for commutting purposes and for convenience.

> Number of males using the service is about 3x more than the population of females using the service. There are more females subscribed to the service, however, than males.

> Users of bike share services may choose to enrol in the Bike Share For All Program. This program offers bike sharing services to low income earners at affordable rates. A trip could be a bike share for all trip meaning that the trip is at a lower price or discounted. Our data shows that more 7x more people do not care to subscribe for the service. The mean ride duration for Subscribers to the Bike Share For All Program is lower than those who are not subscribed to the program.


> Majority of the users are between the ages of 20 and 50 years. We expect ride duration to decrease as the age of the Rider increases. This holds true for our data.


## Key Insights for Presentation

> Typical ride durations are between 4 and 30 minutes. 
> There are about 10x more Subscribers than Customers.
> The number of trips is very high on weekdays and low on weekends. Subscribers typically use bike share services to commute to school or work and typically cover small distances. Customers on the other hand could be Fun Seekers, Recreational Cyclists or other purposes users, and hence cover much more distances.
> The mean ride duration for Customers is more than twice those of Subscribers for every hour of the day and everyday of the week.