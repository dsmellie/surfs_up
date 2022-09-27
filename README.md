# Surfs_Up Analysis

## Project Overview
W. Avy has hired me to analyze the temperature trends in June and December in Oahu to determine if his business is sustainable year-round.

1.	Query the Hawaii.sqlite database to retrieve temperatures for June.
2.	Convert the June temperatures into a list and put the list into a DataFrame.
3.	Generate summary statistics for the month of June.
4.	Repeat steps 1-3 for the month of December

## Challenge Overview

### Overview of Surfs Up Analysis
The purpose of this analysis is to determine whether the temperatures in June and December enable a year-round business.

## Resources
-Data Source: hawaii.sqlite
-Software: Python 3.7.13, Jupyter Notebook 6.4.12, Anaconda 2.2.0

## Results
Comparing the temperature differences between June and December I found that:
-	The lowest temperature in June is 64 degrees Fahrenheit and in December it is 56 degrees.    
-	The average temperature in June is 75 degrees Fahrenheit and in December it is 71 degrees.    
-	The standard deviation in temperature in June is 3.25 degrees while  in December it is 3.75 degrees.
  
  
  Data:

  ![June Temperature Summary](https://user-images.githubusercontent.com/109701875/192625426-1ab2bacd-b0d9-42ff-9fe6-cb1fb1019a20.PNG)
  
  ![December Temperature Summary](https://user-images.githubusercontent.com/109701875/192625416-e2a00883-4ca9-40f5-b819-5984235ed7e8.PNG)
  
## Summary

As can be seen from the data, the temperature in June is slightly higher on average and fluctuates less than in December. However, the overall range of temperatures in both months is within 25 degrees. One additional query I would perform to gather more weather data in June and December would be to analyze the differences in precipitation during these months. A large amount of rain would be negative to any business plans. Another query I would perform would be to compare the water temperatures in these two months. As part of the business plan is a surf shop, the water temperature is very pertinent to the viability of the business. 
