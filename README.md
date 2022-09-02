## Overview of the Analysis
For the sake of this project, I analyzed temperature trends in Oahu for the months of June and December. Using SQLAlchemy, I wrote queries to extract weather data from the weather database to gather statistics on weather measurements throughout the specified months. From the results, I created a dataframe to showcase the summary statistics of the weather data. 

## Results
There were more June temperatures than December temperatures, 1700 compared to 1517. Of the data, we can draw the following conclusions:
- The mean temperature of June rounds up to 75, while December rounded to 71.
- June had a minimum temperature of 64, while December had a minimum of 56.
- The maximum temperature for June was 85 while December was 83.
![surfs_up/june temps.png](https://github.com/noorsami12/surfs_up/blob/6290a3e557a4e971cb1f4c3ade295a8aec1e39b2/june%20temps.png)
![surfs_up/dec temps.png](https://github.com/noorsami12/surfs_up/blob/6290a3e557a4e971cb1f4c3ade295a8aec1e39b2/dec%20temps.png)

## Summary
Ultimately, both June and December have temperatures that would make a surf and ice cream shop a viable option year-round. Both months have a very similar maximum temperature, and their mean temperatures have a difference of only 4 degrees. On average, both months have temperatures in the 70s, making it ideal for a surf and ice cream shop. December is slightly colder then June, but overall the weather remains similar to June. 
Additional queries could be run to determine the amount of precipitation throughout the year, as precipitation will affect surfing and visitation to Oahu. The same queries as used for the temperature could be utilized to filter for precipitation amount in the months of June and December. Another query that could be run is temperatures and precipitation for additional months of the year, to ensure that the data is consistent year-round rather than only two months of the year.
