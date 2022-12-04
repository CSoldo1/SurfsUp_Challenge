# Surfs Up Challenge

## Overview

Aloha! My dream is to open up a surf and icecream shop on the wonderful Hawaiin island of Oahu. I've lined up a few investors to get my business going. One investor, W. Avy, is skeptical about whether or not a surf and shake shop is a feasible, year-round business in Oahu. To address his concerns, I've analyzed tempearture data from the months of June and December - often considered the warmest and coldest months in Hawaii. By using SQLite and SQLAlchemy, I was able to quickly query a database, and provide my potential investors with a detailed summary of temperature trends in Hawaii. 

## Resources
* Data Source: hawaii.sqlite
* Software: Jupyter Notebook, SQLAlchemy, Python 3.7.1

## Analysis 
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the "hawaii.sqlite" database to retreive temperature for the months of June and December. I converted those temperatures to lists, created a dataframe from each list, and generated summary statistics for each month's temperature data. 

## Results
* There is only a 4 degree difference in average temperature between the months of June and December. 
* The minimum temperature in December is almost 10 degrees lower than the June minimum temperature.
* There is little variation in average temperature for both months; the standard deviation from the mean is approximately 3 degrees for each month. 

Summary Statistics for June Temperatures

![June Summary Statistics](https://github.com/CSoldo1/SurfsUp_Challenge/blob/main/June_Temperature_Statistics.PNG)

Summary Statistics for December Temperatures

![December Summary Statistics](https://github.com/CSoldo1/SurfsUp_Challenge/blob/main/Dec_Temperature_Statistics.PNG)

## Summary
Based on temperature, Oahu seems like the perfect place to start a surf and ice cream shop. Summer and winter temperatures are mild, with highs never exceeding 85 F and lows never falling below 56 F. 

Oahu's year-round temperatures are conducive to an icecream shop, but icecream only accounts for 50% of the business. Will the island's weather also support excellent surfing? I should incorporate wind and ocean swell data into my analysis. Sure, the temperature may be nice, but if the waves are non-existant, then patrons may not be attracted to the beach throughout the year.

Year-round precipitation is also a concern. From what I know of tropical locations, there is usually a wet and dry season. There may not be much tourism during the summer monsoons. Perhaps adding this data to the analysis will show W. Avy that a surf and icecraem shop is only feasible as a seasonal business rather than a year-round business. 
