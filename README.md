# Citi Bike Analytics

#### -- Project Status: Completed

## Featured Notebooks/Analysis/Deliverables
* [Tableau Data Story](https://public.tableau.com/profile/jasonzelaya#!/vizhome/CitiBikeAnalytics2_15882072724920/CitiBikeStory?publish=yes)
* [Notebook](https://github.com/jasonzelaya/Citi-Bike-Analytics/blob/master/citi_bike_data_aggregation.ipynb)

## Project Intro/Objective
The purpose of this project is to build a set of data reports to provide answers to city officials' questions about the Citi Bike program in a way that is focused, concise, easy-to-understand, and visually compelling. The Tableau data story answers questions about New York bike usage during the summer and winter seasons, times, locations and demographics to allow Citi Bike to determine the best approach to further increase ridership growth and overall revenue.

### Methods Used
* Data Visualization
* Descriptive Statistics
* Descriptive Analysis
* Exploratory Analysis

### Technologies
* Tableau
* Python
* Jupyter Notebook
* Pandas
* NumPy

## Project Description
The 2019 summer and winter data found in the Citi Bike Trip History Logs was aggregated and used to build a Tableau data story which answers questions about New York bike usage during the summer and winter seasons, times, locations and demographics.

#### Data
The data used in the project was obtained from the Citi Bike Trip History logs from the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage. The data covers the summer and winter seasons of 2019. The months included are January, February, June, July, August, and December. The data includes:
* Trip Duration (seconds)
* Start Time and Date
* Stop Time and Date
* Start Station Name
* End Station Name
* Station ID
* Station Lat/Long
* Bike ID
* User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
* Gender (Zero=unknown; 1=male; 2=female)
* Year of Birth

This data has been processed to remove trips that are taken by staff as they service and inspect the system, trips that are taken to/from any of Citi Bike's “test” stations (which were being used more in June and July 2013), and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it's secure).
* Trip count and mileage estimates include trips with a duration of greater than one minute.
* Mileage estimates are calculated using an assumed speed of 7.456 miles per hour, up to two hours. Trips over two hours max-out at 14.9 miles.
* Only trips that begin at publicly available stations (thereby excluding trips that originate at Citi Bike's depots for rebalancing or maintenance purposes) are included.

#### Questions Being Explored
* How many trips have been recorded total during the chosen period?
* How many trips are taken per day on average?
* What is the average trip duration?
* How many trips are taken during the week?
* How many trips are taken during the weekend?
* What is the median trip duration during the week?
* What is the median trip duration during the weekend?
* By what percentage has total ridership grown?
* How has the proportion of short-term customers and annual subscribers changed?
* What are the peak hours in which bikes are used during summer months?
* What are the peak hours in which bikes are used during winter months?
* What are the top 10 stations in the city for starting a journey? 
* What are the top 10 stations in the city for ending a journey?
* What are the bottom 10 stations in the city for starting a journey? 
* What are the bottom 10 stations in the city for ending a journey?
* How does each station's popularity change over time (by month)?
* What is the gender breakdown of active participants?
* What is the age distribution by gender?
* What is the median cyclist age?
* How does the average trip duration change by age?
* How variable is the utilization by bike ID?   

#### Blockers and challenges
* Not everyone who signs up for the program is answering honestly.
* Trips as short as one minute are included. Trips around one minute long are unlikely and are still probably the results of false starts or bike re-docking.
* Trips longer than two hours are excluded from the data.

## Needs of this project
* Data Exploration
* Data Processing/cleaning
* Writeup/reporting