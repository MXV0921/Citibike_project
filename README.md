# Citibike_project

# An Analysis of NYC CitiBike Data

## Overview of Analysis
August of 2019 was the month we focused on to review data from the NYC Citibike service.  Utilizing Tableau to visualize our CSV file into readable data we analyzed the usage of bikes.  Tableau allows use to look at the data in many different forms. We will discuss our findings, and share some of these images to show the abilities of Tableau as a useful tool.

## Results of Data Review
### Where is CitiBike used the most?
![starting_map](https://github.com/MXV0921/Citibike_project/blob/main/Images/ma_Start_Station.png)
![ending_map](https://github.com/MXV0921/Citibike_project/blob/main/Images/map_End_Station.png)
CitiBike is used the most in Midtown and Downtown Manhattan.  When reviewing Start Station and End Station Maps, we see the same results.

### Inferring why CitiBikes are used
CitiBikes are used most during rush hour times.  Below is a chart showing usage by hour, filtered by gender showing usages at their highest between 7-9 am and again between 5-7 pm.
![heat_map_image](https://github.com/MXV0921/Citibike_project/blob/main/Images/Usage_by_Hour.png)

This hypothesis is also supported by a line chart showing almost all bike 'rentals' are under half an hour, and most bikes are only used for under 10 minutes.  This means they are not being used for excercise or sightseeing.
![line_graph](https://github.com/MXV0921/Citibike_project/blob/main/Images/line_graph_usage.png)

The largest number of users are male and the majority of them are subscribers to the Citibike program, using the bikes on Weekdays.
![piechart](https://github.com/MXV0921/Citibike_project/blob/main/Images/by_gender.png)
![gender_daily_usage](https://github.com/MXV0921/Citibike_project/blob/main/Images/subscribers.png)

## Should Des Moines Get CitiBikes
Des Moines population likely does not support a CitiBike program.  While we would need to do considerably more research to finalize this hypothesis, our analysis shows that this program is successful due to the high population density, commercial industry and traffic patterns of New York City.  Des Moines is a much smaller city and New York would not be a good comparison before making such a large investment.

![bike total usage](https://github.com/MXV0921/Citibike_project/blob/main/Images/bike_usage.png)
A majority of the inventory of the bikes get very little total usage by time ridden or by total rides take, but need to be available for subscribers who are using them as a part of their commute home. There are many bikes sitting around waiting to be used, and this is a considerable investment necessary.
![bike_total_rides](https://github.com/MXV0921/Citibike_project/blob/main/Images/bike_usage2.png)

## If We Move Forward
### More data needed
There is a high likelihood that the data we received was corrupt, as seen in our 'Avg Trip Duration' data.  This sorted data by users year of birth and our highest amount of usage was by those born in the year 1891.  We will need to investigate other months to see how this data may have been skewed.

![avg trip duratio](https://github.com/MXV0921/Citibike_project/blob/main/Images/Avg_trip_duration.png)

### Moving Ahead
If our company does decide to move forward, we should focus our marketing towards males, as they are the largest users and account for over 65% of all rides taken.  
![by_gender](link)


### Links to Tableau Dashboard
CitiBike Challenge
![link to dashboard](https://public.tableau.com/app/profile/mark.vogel/viz/Citibike_Challenge_16572293275230/Story1)
