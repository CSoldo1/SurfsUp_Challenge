# Surfs Up Challenge

## Overview

Time to open up a Surf and Shake shop in Oahu, Hawaii. Serving surfboards and ice cream to locals and tourists. 
How is the weather. Weather analysis using SQLite and SQL Alchemy. 
weather database from the hawaiin islands
Summary statistics for the months of June and December
Temperature data in order to determine if the surf and ice cream shop business is sustainable year-round

## Resources
* Data: hawaii.sqlite
* Jupyter Notebook
* SQL Alchemy

## Analysis 
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the "hawaii.sqlite database to retreive temperature for the months of June and December. I converted those temperatures to lists, created a data frame from each list, and generated summary statistics for each month's temperature data. 

## Results
*There is only a 4 degree difference in average temperature between the months of June and December. 
* The minimum temperature in December is almost 10 degrees lower than the June minimum temperature.
* There is little variation in average temperature for both months; the standard deviation from the mean is approximately 3 degrees for each month. 

Summary Statistics for June Tempeartures
!(https://github.com/CSoldo1/SurfsUp_Challenge/blob/main/June_Temperature_Statistics.PNG)

Summary Statistics for December Temperature
!(https://github.com/CSoldo1/SurfsUp_Challenge/blob/main/Dec_Temperature_Statistics.PNG)

## Summary
Based on temperature, Oahu seems like the perfect place to start a surf and ice cream shop. Summer and winter temperatures are mild, with highs never exceeding 85 F and lows never falling below 56 F. 

Oahu's year-round temperatures are conducive to an icecream shop, but icecream only accounts for 50% of the business. Will the island's weather also support excellent surfing? I would add data about wind and ocean swells to my analysis. Sure, the temperature may be nice, but if the waves are non-existant, then patrons may not be attracted to the beach throughout the year.

The same thing holds true with precipitation. From what I know of tropical locations, there is usually a wet and dry season. There may not be much tourism during the summer monsoons. Perhaps adding this data to the analysis will show W. Avy that a surf and icecraem shop is only feasible as a seasonal business rather than a year-round business. 
