# Analysis of PyBer's Ride Share Data by City Type

## Overview

After being hired as a data analyst by PyBer, a Python-based, ride-sharing app company, we were
tasked with performing exploratory analysis on two large CSV files of city and ridership data. 
Additionally, we were asked to create charts detailing the relationship between type of city and 
the number of riders and drivers, as well as percentage of total fares, riders, and drivers, by 
the type of city. 

## Results

Our analysis revealed a basic disparity between the urban and rural cities, with urban cities having 
higher rates of lower fare trips, and rural cities having less frequent trips with higher average fares, 
while the suburban cities fell in between the urban and rural cities. 

![PyBer Summary DataFrame](https://github.com/greensleeves8/PyBer_Analysis/blob/main/analysis/PyBerSummary.png)
![Scatterplot of total rides and fares by city type](https://github.com/greensleeves8/PyBer_Analysis/blob/main/analysis/Fig1.png)

In addition, the urban cities had much higher counts of drivers than either the suburban or rural cities.

![PyBer Driver Count](https://github.com/greensleeves8/PyBer_Analysis/blob/main/analysis/Fig4.png)

Due to the higher rates of usage, urban cities generated the majority of the total fares received, despite having
lower average fares than the suburban or rural cities. 

![PyBer % Total Fares](https://github.com/greensleeves8/PyBer_Analysis/blob/main/analysis/Fig5.png)

## Summary

Three business recommmendations I would make based off of the PyBer data: 

- The area with the highest room for growth is in rural cities. The data suggests that part of the issue
 may be the lack of drivers in rural areas:

![Pie Chart, Driver % By City Type](https://github.com/greensleeves8/PyBer_Analysis/blob/main/analysis/Fig7.png)
	
Though the average fares for rural areas are much higher than suburban or urban cities, the number of total 
trips is low. A program to bring in more drivers or a marketing campaign in rural areas would serve a dual 
purpose, increasing the number of drivers available, while also raising awareness of the PyBer service among 
potential riders. 

- Suburban areas share the higher average fares of rural areas with much of the rider frequency of urban areas, 
so I believe that the best course of action in suburban areas would be to encourage more frequent use. I would 
focus on getting users who may be car owners to use PyBer for short errands as a way to save wear and tear and 
gas expenses. 

- In urban areas I would try to encourage longer trips overall. While shorter, more frequent trips are much of 
the urban business, there are enough drivers available to accomodate longer trips, which would drive up the 
average total fares in urban areas. I would encourage riders to use PyBer for trips to the nearest airport or 
regional travel/day trips for non-car owners.  
	
