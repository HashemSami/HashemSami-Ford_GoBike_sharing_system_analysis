# Bike trips activity on the Ford GoBike sharing system in San Francisco Bay area.

## Dataset

The dataset includes information about 183,412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The attributes include the trips durations, station information, bike ids, and weather the customer is a subscriber or casual, as well as additional measurements such as gender and birth year of the customers.
dataset library and documentation can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data)

## Summary of Findings

In the exploration, I found that there was a strong relationship between the trip durations and the customer type, with modifying the rents dates to week days to capture the daily activity, a strong relationship was also shown between these variables.
The relationships with the trip durations were showing an increase for the casual customers, and this increase was shown during the weekends. on the other side, daily activity was increasing during the workdays, and that increase was happening thanks to the subscriber customers that are making more that 89% of the renting activity recorded on the data.

Outside of the main variables of interest, when plotting the bike ids vs the average trips durations, I found that there are some specified bikes (that has ids more than 4000) that were recording the higher duration trips, and I thought these bikes might belong to a station or area that is making the longer durations. But when plotting the station locations (latitude and longitude) and project the bike id markers on these locations, I found that these bike ids were equally distributed, and they are not related to the duration increase that was found on the dataset.

## Key Insights for Presentation

For the presentation, I focused on presenting the causes of the higher trip durations found on the dataset, also the higher activity rents that was recorded in terms of the day of the week. I started by introducing the daily activity distribution, followed by the trips durations distributions, then the customer types distributions.

Afterwards, I showed how these variables are affected by each other, like how the customer type has an impact on the trip durations, and the impact on the daily activity.
