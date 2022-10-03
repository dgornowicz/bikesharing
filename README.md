# Bikesharing
An Analysis of New York City CitiBike bikesharing data from August, 2019, with Tableau


## Tableau Link
[Challenge Link](https://public.tableau.com/app/profile/david.gornowicz/viz/NYCCitiBikeChallenge_16631130352620/sheet8)


## Resources
- Tableau
- Tableau Public
- [CitiBike Data](https://s3.amazonaws.com/tripdata/index.html)


## Most Common Checkout Locations

<img width="497" alt="top_starting_locations" src="https://user-images.githubusercontent.com/102050273/193487035-f6cb7d0e-384c-47fc-82df-a98b4f6f3ff9.png">

This map shows which locations in NYC have the most bike checkouts. We can see the area just South of Central Park is generally the busiest.


## Most Common Checkout Times

<img width="488" alt="checkout_times" src="https://user-images.githubusercontent.com/102050273/193485888-4f512b8a-49f4-4ea2-b733-2b1045be8239.png">

This plot shows which times of day have the highest amount of bike checkouts. We can see the hours with the most checkouts are from 4-7 PM. 


## Most Common Checkout Times by Day

<img width="274" alt="daily_checkout_time" src="https://user-images.githubusercontent.com/102050273/193486288-261c24e2-fffa-4a27-b0ce-8649c2f3c53f.png">

This plot shows which times of day have the highest amount of bike checkouts for each day of the week. We can see there is a distinct change in bike usage from Weekdays to Weekends. There is a clear rush hour in the morning and evening during the week and a more even distribution throught the afternoon on the weekends.


## Trip Duration Trend

<img width="492" alt="trip_duration" src="https://user-images.githubusercontent.com/102050273/193486027-6a168221-dd0b-48a6-bac7-af022ceaf021.png">

This plot shows how long trips last by minute. We can see that the most common duration is 5 minutes (~145k trips) and that the amount of trips by minute rapidly and consistently declines (~1k trips last 60 minutes).


## Trip Duration Trend by Gender

<img width="482" alt="trip_duration_gender" src="https://user-images.githubusercontent.com/102050273/193486618-9cc1f542-a4ec-40d2-b9f1-96a7889ab11e.png">

This plot shows how long trips last by minute and by gender. We can see Men and Women follow the same trend, with more Men than Women checking out bikes.


## Bike User breakdown by Subscriber Status

<img width="178" alt="customer_sub_piechart" src="https://user-images.githubusercontent.com/102050273/193486891-d6818df4-302c-4e3c-a392-2f237e44fefa.png">

This plot shows the portion of CitiBike users that are subscribers and not subscribers. We can see 80% of users are subscribers.


## Bike User breakdown by Gender and Subscriber Status

<img width="193" alt="daily_subscriber_heat_map" src="https://user-images.githubusercontent.com/102050273/193487204-a7d76687-015b-4442-9e47-154e75993ca2.png">

This plot shows the amount of CitiBike users that are subscribers or not, by day and gender. We can see the effects of the previous plots aggregated here.


## Results
Based on the data gathered:
- Males are the most frequent and populus customer 
- Trips are usually less than 30 minutes and rarely exceed an hour
- THe highest density of trips occurs after work between 5pm - 7pm on weekdays

### Two Additional Visualization Suggestions
- A graph that charts rides per day. This would be useful because it could highlight some key seasonal trends
- A chart that uses a heat map to represent the age/birth year of subscribers. This could help show areas of customers that may need to be targeted more or in a different manner.
