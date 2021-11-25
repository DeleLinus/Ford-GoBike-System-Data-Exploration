# Ford GoBike System Data Exploration
## by Ayanwoye Gideon Ayandele

## Slide Preview
![SLide_communicate_findinds](https://user-images.githubusercontent.com/58152694/143484454-a2fb6bf8-c964-4ba2-8584-596ac6259696.gif)


## Dataset

The data consists of information regarding 183,412 rides made in a bike-sharing system covering the greater San Francisco Bay area in 2019. The dataset includes 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude','start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type','member_birth_year', 'member_gender', 'bike_share_for_all_trip'). The dataset can be found [here](https://www.fordgobike.com/system-data).
Upon proper data cleaning, the dataset was reduced and feature-engineered into 11 columns with  the new columns being: 

> day_of_week: to store week day number from start_time.
> start_hour: to store hour number from start_time.
> time_of_day: to store the time of the day from start_hour
> duration_min: to store the duration in minutes.
> user_age: to store the user's age from member
> user_age_bin: grouped/binned ages for age group exploration


## Summary of Findings

Subscribers and customers bikes usage was different:

> The day of the week that most trips are taken (Thursday) is NOT dependent on if a user is a subscriber or a customer. However, it was discovered that Subscribers mostly used bikes on workdays (Monday - Friday), while customers bikes usage was about the same for the whole week with a huge increment on Saturday and Sunday
> On average, Subscribers' trips mostly last for (10-11) minutes, while customers mostly last for (23-24) minutes.
> Customers rides were more likely to last more than one hour compared to subscribers.
> Customers often start the trip in the afternoon where as Subscribers starts mostly in the morning followed by afternoon.
> Most rides for subscribers started at 8 or 17. While most customer rides started at 17.
Average trip duration in minutes:
> On average, rides on the weekend (Saturday and Sunday) lasted longer than the other days.

## Key Insights for Presentation

For the presentation:\
* I focus on just  looking at the time of the day and the day of the week that most trips are taken
* how long does the average trip take? and 
* check if the results depend on if a user is a subscriber or a customer.\
* The presentation showed that there indeed is a dependency of the average trip duration on if a user is a subscriber or a customer. On average, customers rides lasted longer than subscribers rides on every day of the week and time of the day


## Feedback

If you have any feedback, please reach out to me at ayangidel@hotmail.com
