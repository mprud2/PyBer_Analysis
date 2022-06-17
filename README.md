# PyBer_Analysis
Module 5: Matplotlip, SciPy, and NumPy


## Overview
* Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
* Determine the mean, median, and mode for the following:
   * The total number of rides for each city type.
   * The average fares for each city type.
   * The total number of drivers for each city type.
* Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
  * The number of rides for each city type.
  * The fares for each city type.
  * The number of drivers for each city type.
* Create a pie chart that visualizes each of the following data for each city type:
  * The percent of total fares.
  * The percent of total rides.
  * The percent of total drivers.

Finally, we were asked to prepare an Executive Summary DataFrame as well as a visualization showing the weekly fare by city type

## Results

### Bubble Chart Displaying Average Fare vs Total Rides 
The PyBer analysis found that fares in Urban city types are by-far-and-away the greatest contributer to PyBer's overall revenue, but also the biggest pool of drivers, most overall rides provided, and lowest average fare.  The facts that Urban rides were both the greatest contributor to revenue while simultaneously the lowest average fare may seem counterintuitive, but the average fare is outweighed by the sheer volumes of Urbadn rides (and drivers).  This can be observed in Fig.1, which plots the average fare against the total number of rides, with the size of the bubble being indicative of the number of drivers in each location.  
![Fig1](https://user-images.githubusercontent.com/104801614/174266780-56df83dd-da29-4727-8461-f81313d24844.png)

Fig 1: Plot of PyBer Ride Sharing Data from 2019

### Measures of Central Tendency for Total Numer of Rides, Average Fares, and Total number of Drivers

#### Ride Counts
Urban: 
 * mean = 24.62 
 * median = 24.0
 * mode = 22 (7 occurrences)
 
Suburban: 
 * mean = 17.36
 * median = 17.0
 * mode = 17 (7 occurrences)
 
Rural: 
 * mean = 6.94 
 * median = 6.0 
 * mode = 6 (5 occurrences)


#### Average Fare
Urban: 
 * mean = $24.53 
 * median = $24.64 
 * mode = $22.86 (5 occurrences)
 
Suburban: 
 * mean = $30.97
 * median = %30.75
 * mode = $17.99 (3 occurrences)
 
Rural: 
 * mean = $34.62
 * median = $37.05
 * mode = $37.05 (2 occurrences) 


#### Number of Drivers
Urban: 
 * mean = 36.68
 * median = 37.0
 * mode = 39 (86 occurrences)
 
Suburban: 
 * mean = 13.71
 * median = 16.0
 * mode = 20 (79 occurrences)
 
Rural: 
 * mean = 4.3
 * median = 4.0
 * mode = 1 (32 occurrences)

### Box-and Whisker Plots

#### Number of Rides by City Type
![Fig2](https://user-images.githubusercontent.com/104801614/174266811-74491ef9-f2c3-4f7a-88a6-b957b4ca8be5.png)

#### Ride Fare Data by City Type
![Fig3](https://user-images.githubusercontent.com/104801614/174266828-7df4ac22-a412-4e36-be9b-81927dbff4ac.png)

#### Driver County by City Type
![Fig4](https://user-images.githubusercontent.com/104801614/174266842-2fd13ac4-788c-41f1-9ce2-6d3d364ab830.png)


### Pie Charts

#### Percent of Total Fares
![Fig5](https://user-images.githubusercontent.com/104801614/174266861-771e7e24-3861-4e70-94a2-38f416232f72.png)


#### Percent of Total Rides
![Fig6](https://user-images.githubusercontent.com/104801614/174266885-66ccb7bc-f684-4adc-b894-7ad01bb5d5c0.png)

#### Percent of Total Drivers
![Fig7](https://user-images.githubusercontent.com/104801614/174266912-97d3917a-4bc8-4845-a950-991d084ed6d3.png)


### Total Fares by City Type
![PyBer_fare_summary](https://user-images.githubusercontent.com/104801614/174274538-00699ced-b5dd-4eef-bc58-42b798d12ba5.png)

## Summary
After analyzing the data, it is clear that Urban cities are dominating the revenue results.  Nearly seven out of every eight PyBer drivers work in an Urban area.  Therefore, we would recommend that PyBer should consider recruiting more Suburban and Rural drivers to determine if their customers needs are being met in those locations.  It is possible that potential customers in those areas are not using PyBer because there are not enough PyBer drivers to meet their needs.

It is also observable that there are a spike in total fare in the fourth week of February (see: "PyBer Fare Summary" Figure).  PyBer may want to ensure that there are more drivers available during that period to accommodate the surge in use.  

Finally, PyBer may want to attempt to collect data on pick-up locations and destinations.  While a driver may be counted as an "Urban" driver, it is possible that a ride could start in an Urban location and end in a Rural one (or vice versa).  This kind of data collection will enable PyBer to make more educated decisions about where to use their drivers, or provide guidance to drivers ahead of time.
