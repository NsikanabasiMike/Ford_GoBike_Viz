# Exploring Ford GoBike System Data 
## by Nsikanabasi Essiet


## Dataset

> Ford GoBike System Data includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in USA.
In the dataset, there are 183412 records of fordgobike trips and 16 specifications(`duration_sec`, `start_time`, `end_time`, `start_station_id`, `start_station_name`, `start_station_latitude`, `start_station_longitude`, `end_station_id`, `end_station_name`, `end_station_latitude`, `end_station_longitude`, `bike_id`, `user_type`, `member_birth_year`, `member_gender`, `bike_share_for_all_trip`).
You can download or find more details about the data [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

I used histograms to find out that:
- most trips last for 600 seconds.
- busiest trip take-off and ending time is 17:00 and 03:00 is the least.
I'm going to use these histograms in my presentation as it gives insight on the durations of trips and time.

Also, I used bar charts to find out that:
- Majority of trippers were born between 1950s and 2000
- Subscribers make trips more than customers with a ratio of 166k to about 18k respectively.
- Those who do not share bikes for all trips dominate over those who share.
- Thursday is the busiest day of trips while Saturday is the least
I'm going to use the last barchart in my presentation because day very important in making decisions.

Then I used scatter plots to find out that:
- Subscribers dominate because they have members of birth year between 1940 to 2000. Customer only have members from 1950 to 2000.
- Trip duration does not contribute to subscriber's dominance

Afterwards, I used heatmaps to gain the following insights:
- There is a somewhat strong linear relationship between start and end stations ids. The relationship suggests that most frequent stations ids are between 0 and around 300
- The most frequent bike_ids are between 5000 and 6000

I also used clustered bar charts to find that:
- About 1% of Customers do not share bike for all trip, no customer shares bike. About 80% of Subscribers do not share bike, while about 1% of subscribers share.

Finally, I used boxplots to find that:
- Majority of trips are made by members who share 1990 birth year.
- Those who were born in late 1990s frequently share bike for all trips.
I'll be using this as well in my presentation because it covers a lot of plots to show the relationship between five variables in the dataset.

## Key Insights for Presentation

For the presentation, I am interested in plotting histograms to showcase trips busiest and least busiest days, busiest trip take-off and ending times.