# (Ford GoBike System Data Exploration)
## by Vrushabh Suchak


## Dataset

> Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose.

> The Ford GoBike System Data is straightforward and intuitive to understand. This data has been collected efficiently, providing a valuable collection of data to work with and draw conclusions from. 

>This notebook uses data collected from June 28th, 2017 through December 31st, 2017. There were approximately 519,700 bike rides in the San Francisco Bay area of California, USA. 

> The column header descriptions are as follows:
- Trip Duration (seconds)
    - Start Time and Date
    - End Time and Date
- Start Station ID
    - Start Station Name
    - Start Station Latitude
    - Start Station Longitude
- End Station ID
    - End Station Name
    - End Station Latitude
    - End Station Longitude
- Bike ID
- User Type (Subscriber or Customer)
- Distance travelled (in meters)
    
> I added the following columns in my cleaning efforts:	
- Start Time Month
- Start Time Weekday
- Start Time Hour
- Duration in Minutes
- Distance Travelled (in meters)


## Summary of Findings

1. **Duration of bike rides:** The distribution of duration of bike rides was right skewed. Bike ride duration ranges from less than 1 minute to 1400+ minutes with mean around 18 minutes.
2. **Customer Usage:** Customer usage increased during weekends compared to weekdays.
3. **Subscriber Usage:** Subscribers used the GoBike system mostly during weekdays. They start their trip mostly during 8-9 am and 4-6 pm which is usually the working hours. The subscriber usage also decreased during the weekends compared to usage during weekdays.
4. **Average travel time:** The average time travelled by the subscribers is less than that of customers. Average time travelled by subscribers was 42 minutes and average time travelled by customers was 11 minutes.

## Key Insights for Presentation

> Subscribers usage is mostly during the rush hours of morning and evening. Subcriber Usage during the weekends decrease drastically suggesting that they use bike rides mostly for work purpose. In contrast, customers go on bike rides mostly on weekends suggesting that they use it for leisure purpose.

> Adding the user type to the analysis revealed different behavior usage between customers and subscribers. The data suggests that the customers are casual riders such as tourists or students on a vacation or holiday. This is evident from the investigation that customer usage increases on the weekends. In contrast, the investigation suggests that subscribers are daily commuters or full time students who use the Ford GoBike system during weekdays and mostly for shorter distances. They mostly rent bike before or after a typical work or school day.

## Resources 

[StackOverFlow](https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude)<br>
[Pandas documentation](https://pandas.pydata.org/docs/user_guide/)<br>
[Numpy documentation](https://numpy.org/doc/stable/user/)<br>
[Matplotlib documentation](https://matplotlib.org/3.2.1/tutorials/index.html)<br>
[Seaborn documentation](https://seaborn.pydata.org/)<br>
[Github](https://github.com/chelseymarie6/Communicate-Data-Findings/blob/master/Communicate_Data_Slide_Deck.ipynb)