# Bike sharing analysis with Ford GoBike dataset
## by Kyung Nam Kim


## Dataset

> The data consists of information regarding bike riding service by Ford GoBike, including age, timeframe, gender, station, and others. The dataset can be found in Ford GoBike website.
Dataset: (https://s3.amazonaws.com/fordgobike-data/index.html)
The data consisted of 16 different variables such as age, gender, weekday, time and others. I removed user datas over 60 years old since they only consists 5% of whole user group. Also, I generated new fields such as age group in order to make grouping and analyze the date by using groups.
Ford GoBike spreaded the service to San Francisco, Oakland and San Jose. However, it's hard to imagine traffic in those areas, so, I decided to focus on San Fancisco area.


## Summary of Findings

> There were 1.6 million rides. In general, people in 30-40s rode bike the most. People in 40-50s rode the bikes the least. Also, both 20-30s and 30-40s increased a lot while 40-50s showed mediocre increase. 20 to 40 years old people took the more than 70% of bike rides. Among those, 30 to 40 years old people's rides account more than 40%of all bike rides. Male took around 76% of all bike rides, and female took around 24% of them. People use this service on weekdays more than weekends. 8am and 5pm are the peak hours for this service. Also, people use this service when they are in lunch time as well. Percentage of subscribers is almost %88.15. Percentage of customers is almost %11.85. Customers' rides seems increasing slightly but subscibers' rides reached 6 times more than customers' on October 2018. There is a decrease on November 2018 for subscribers but it seems like it is related with winter season. Subscribers' average trip duration is around 11 minutes. Customers' average trip duration is around 28 minutes. Subscribers and customers trip distance were about the same, which is slightly more than one mile. 90% of bike rides take place on weekday. The peak bike rides time for all members is around commute time.


## Key Insights for Presentation

> For the presentation, I focus on age, gender, monthly trend, and trend by user types. I start by introducing the age distrubition, monthly bike hiring trend, followed by age group distribution, then plot the monthly trend by user types.
