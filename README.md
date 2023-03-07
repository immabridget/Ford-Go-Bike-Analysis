# Ford Go Bike Data Exploration



## Dataset

Ford GoBike is a publicly available dataset that includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.The data contains duration (secs) and others such as DateTime, customer type, gender, as well as some additional variable for each bike ride. It has 183,412 rides.
The dataset can be downloaded from [Here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings

In my investigation, I discovered that trips typically last 600 seconds on average and that Tuesdays and Thursdays are the busiest days. There are few trips on weekends compared to  weekdays. The higher trip records for the eighth and ninth hours of the morning and the seventeenth and eighteenth hours of the evening are something else I discovered to be fascinating. The bustle at the two times of the day may be responsible for this. Most of the rides were taken by subscribers, and Male gender took more trips than other genders.e taken by men. Users at the age of 30 years take the longest trip rides.

I discovered that customers spend far more time on their trips than subscribers do, and women typically ride for longer periods of time.The number of rides on any given day does not appear to be impacted by user type. Only subscribers are allowed to share bike all day.

## Key Insights for Presentation

In the Presentation, I will concentrate on the frequency of rides per hour, day, and user type. I begin by using Countplot to examine trip frequencies by hour, day of the week, and user type. I will also look at how the trip duration is affected by age.

I will then go over each of the categorical variables individually. I will look at how trip duration is impacted by user type.  I will use boxplot to visualize this. The following section I will use point plots to discuss the other two categorical variables, days and user type. To ensure that it is obvious that each quality variable differs between plots, I have taken care to utilize distinct color palettes for each of them.