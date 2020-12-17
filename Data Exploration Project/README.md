# Project: Ford GoBike System Data Exploration


## Dataset

> The investigation explored the `Bay Wheels Trip History Data` for `Ford GoBike System` for bike rides taken in the year `2017`. The data consists of information regarding 519700 records of bike trips, including the duration, start and end time, start and end station, bike id, start and end station id, latitude and longitude and user type. The dataset can be found [here](https://s3.amazonaws.com/baywheels-data/2017-fordgobike-tripdata.csv.zip) and documentation of each variable can be found [here](https://www.lyft.com/bikes/bay-wheels/system-data). The original dataset was assessed and cleaned to solve 4 quality issues before exploring the data.


## Summary of Findings

> During exploration of the dataset, the following findings were discovered:
> * The number of rides per user was greater for subscribers compared to customers.
> * Larger number of rides taken occured during weekdays (`Monday` to `friday`) with most number of rides taken on `Tuesday` than on weekends (`Saturday` and `Sunday`).
> * Most rides were usually taken in daytime between the `07:00 am` and `07:00` pm.
> * A larger number of rides were taken at `San Francisco Ferry Building (Harry Brudges Plaza)` start station.
> * Longer rides were preferably taken by customers even though subscribers took a larger number of rides.
> * Longer rides were also preferably taken by customers on weekends (`Saturday` and `Sunday`) than weekdays (`Monday` to `Friday`)
> * The longest rides were taken by by customers in the month of June.
> * Longer rides were taken by customers between `01:00`am ato `)5:00`am.
> * The Longest rides were also taken by customers at the following start stations: `San Francisco Ferry Building (Harry Bridges Plaza)`, `The Embarcadero at Sansome St` and `Montgomery St BART Station (Market St at 2nd St).


## Key Insights for Presentation

> The presentation focused on time-related factors like `start day`, `start month`, `start hour` of each ride, `user type`, `start station` and the relationship these variables had on the number of rides taken and the average ride duration`. 

> The distribution of each of the individual variables were first plotted using a histogram for the ride duration, countplots for `start day`, `start month`, `start hour` , pie chart and count plot for `user type`. Afterwards the relationship between `start day`, `start month`, `start hour` and `user with the logarithm transformation of ride duration were plotted using violin plots. 

> Using boxplots, the relationship between `start day`, `start month`, `start hour` with the ride durationrelationship between `start day`, `start month`, `start hour` with the ride duration depending on the varying `user type` was observed. 

> Using pointplots, the relationship between `start month`and `start hour` with the ride duration depending for differents days of the week was also observed.

> Using Boxlots, the number of rides per `user type` for the top 10 start stations was also plotted.

