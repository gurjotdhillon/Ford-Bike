#Ford GoBike Data Exploration
## Overview
This project explores the Ford GoBike dataset to understand customer behavior and usage patterns in their bike-sharing system. The analysis uses Python libraries like pandas, matplotlib, and seaborn to clean, analyze, and visualize the data.

## Objectives
The primary goals of this analysis are to:

* Identify the busiest stations in the system.
* Determine peak usage hours and how they differ by gender.
* Analyze trip patterns across different days of the week.
* Explore the age and gender demographics of riders.
* Compare the number of subscribers vs. casual customers.
* Investigate the correlation between rider age and trip start time.
* 
Dataset
The dataset used in this project was provided by Udacity as part of its Data Analyst Nanodegree program. It contains information about individual rides made in the Ford GoBike bike-sharing system in the San Francisco Bay area.

## Data Wrangling and Cleaning
The following steps were performed to prepare the data for analysis:

Converted start_time and end_time columns to datetime format.
Created new columns for start_date, end_date, start_day, end_day, start_hour, and end_hour.
Created a period column to categorize trips into morning, afternoon, and night.
Calculated rider age based on member_birth_year.
Removed rows with missing values.
Removed unrealistic age values (above 80 years old).


## Findings
Busiest Stations:
San Francisco Caltrain Station 2 (Townsend St at 4th St) is the busiest station overall.
Market St at 10th St is the most popular starting station.
Peak Hours:
Peak usage occurs during commute hours (7-9 AM and 4-6 PM) on weekdays.
Weekend usage patterns differ, with more activity in the afternoon.
Gender and Age:
Males make up the largest proportion of riders.
The average rider age is 34 years.
User Type:
The majority of riders are subscribers.
Day of the Week:
Thursday is the most popular day for bike trips.

## Visualizations
The project includes several visualizations to illustrate the findings, including:

Bar charts showing the busiest start and end stations.
Histograms displaying the age distribution of riders.
Count plots showing the distribution of trips by day of the week and gender.
Heatmap illustrating the correlation between rider age and trip start time.
Line plots showing the distribution of trips by hour and gender.
Code
The code for this analysis is available in the ford_gobike_exploration.ipynb Jupyter Notebook file.

## Libraries Used
pandas
matplotlib
seaborn
Additional Notes
The analysis assumes that the distance between the start and end station represents the total distance traveled.
Further analysis could be conducted to explore factors like trip duration, distance traveled, and the impact of weather on bike usage.
