# PyBer_Analysis

## Overview of PyBer Analysis

PyBer is a Python-based ridesharing app company in which we are tasked to be able to analyze their collected metrics on geographical and fare information. The information gathered can be organized and charted to be able to assist the company in administrative decision making such as adjusting their prices and regions of focus. We are given two data sets in [city_data.csv](/Resources/city_data.csv) and [ride_data.csv](/Resources/ride_data.csv). Python is used in this analysis in conjunction with the Pandas library and PyPlot with Matplotlib to be able to create line graphs. The outputted code is in [PyBer_Challenge.ipynb](/PyBer_Challenge.ipynb).

## PyBer Analysis Data Results 

A completed and processed Dataframe with the summary of results following merging the data sets was created as follows: 

![Summary](/analysis/SummaryTable.png) 

Focusing on the region type, `.groupby(["type"])` was used to obtain each of the column values prior to merging them in the 6th comment. 

Additionally, we were able to plot the total fare over time for each region in the following: 

![Fare Summary](/analysis/PyBer_fare_summary.png)

## PyBer Analysis Summary and Recommendations

Based on the summary table, we see that the heaviest users are those who take rides in Urban areas, with the least being rural areas. We see as well that despite being the lowest users of the service, rural users experience the highest fares per ride and highest fares per driver, with urban users experiencing the opposite. Proportionately as well, the rural region has the least drivers, with the urban regions having the most. 

We see as well that across all three city types that the time between Februrary and March has the highest fares per the Fare Summary table. 

An initial recommendation would be to track distance and trip durations to help us further normalize the data to perhaps reveal additional trends. 

A potential decision to inventivize usage of the app in rural areas could be to subsidize driver pay in Rural areas to drive the rider fare cost down, such that there would be more drivers due to the pay and more users interested in using the app if rural prices are more affordable. 

Urban rides are likely to be shorter due to aspects of urban/city sprawl; however, they tend to be a lot longer due to the nature of urban traffic. It could be possible depending on the aforementioned metrics to increase the fare of city rides due to this reason to assist in incentivizing more full-time drivers to diversify their regions, perhaps increasing attention to rural and suburban areas. 

An additional recommendation would be to research alternative public tranporation fares in the area(s) to ensure that the company is still able to remain competitive, especially if rural prices are higher due to distance/scarcity. 

## Resources

- [city_data.csv](/Resources/city_data.csv) and [ride_data.csv](/Resources/ride_data.csv) as provided by UCSD Data Science and Visualization program
