# surfs_up

## Overview 
The main purpose of this challenge is analyse a weather data set to determine if a surf and ice cream shop can be successful in Oahu, Hawaii. Specifically, temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

# Resources
Software:
- SQLite
- Flask
- Python
- Jupyter notebook

# Results

## Derivable 1: Determine the Summary Statistics for June.

Using Python, Pandas functions and methods, and SQLAlchemy, the date column of the Measurements table in the hawaii.sqlite database was filtered in order to retrieve all the temperatures for the month of June and December. Then the temperatures were converted to a list, a DataFrame was created, and the summary statistics was generated.

![june_temperatures.png](https://github.com/jeperes/surfs_up/blob/main/Resources/june_temperatures.png)

## Derivable 2: Determine the Summary Statistics for December.

![december_temperatures.png](https://github.com/jeperes/surfs_up/blob/main/Resources/december_temperatures.png)

## Major points 

- The average temperatures of June and December have a small difference of 74.9 and 71.0 degrees.
- The maximum temperature of both months are very similar, 85 and 83 degrees.
- The minimum temperature drops from 64 in june to 56 in December, what could be a concern since is a ice cream shop.

# Summary

The temperatures between June and December are slightly different, what is good news for the business. Ivy would still be able to open a successful ice cream and surf shop in Oahu. I would create another query to show the precipitation difference between June and Decemcember.

