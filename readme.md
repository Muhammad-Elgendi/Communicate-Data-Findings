# Bay Wheels Ride Data Exploration and Visualization In August 2020
## by Muhammad Elgendi


## Dataset

This  <a href="https://s3.amazonaws.com/baywheels-data/index.html">dataset</a>   was collected from trips in August 2020 and it has 152446 anonymized records.
Every record has the following variables and they can be catagorized into :

* Bike info : ride_id and rideable_type variables.
* Trip time : started_at and ended_at variables.
* Station info : start_station_name, start_station_id, end_station_id, end_station_name, start_lat, start_lng, end_lat and ent_lng.
* User info : member_casual variable.

Visualizations below are created from the cleaned data to facilitate the discovery of usage patterns and user characteristics.

## Summary of Findings

 >There were more casual users using the bike-sharing system than members overall, both of which ride the most during Saturdays. Different usage patterns and riding habits are observed between the two types of users. Casual users used the system heavily on weekends, whereas members used it intensively on Tuesday. Most of the usage was observed between 5 PM and 6 PM for all users.


## Key Insights for Presentation

 * Casual users contributed the majority of the bike usage in August 2020, about 59%, while about 41% were consumed by members. Both casual users and members ride the most during Saturday. Casual users use Bay Wheels the most on weekends, whereas members have roughly equal usage through the week with peaks on Saturdays and Mondays.

 * Casual users who used Bay Wheels on Sunday and Monday have longer trips on average than all other casual users, with trips being shorter in the middle of the week (namely: Monday, Tuesday, and Wednesday), whereas members who used Bay Wheels on Tuesday have longer trips on average than all other members.

 * The pattern of usage is different between casual users and members.
For members there exist a consistent usage over the whole week, their intense usage on Saturday is between 11 AM and 6 PM and on Sunday their usage is focused between 12 PM and 4 PM and for all other weekdays, the focused usage is between 5 PM and 6 PM.

 * For casual users, their usage is intense on Saturday, Sunday, and Friday and light in the rest of the days. as members, their usage on Saturday is between 11 AM and 6 PM But on Sunday their usage is focused between 1 PM and 5 PM, and for Friday there is an intense usage between 5 PM and 6 PM.

 * Most of the usage was observed between 5 PM and 6 PM for all users.
