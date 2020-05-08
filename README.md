# Citi Bike Analytics

#### -- Project Status: Completed

### Technologies
* Tableau
* Python
* Pandas, jupyter
* NumPy

#### The Tableau dashboards can be found [here](https://public.tableau.com/profile/jasonzelaya#!/vizhome/CitiBikeAnalytics2_15882072724920/CitiBikeStory?publish=yes).

### Data
Citi Bike Trip Histories
The data covers the summer and winter seasons of 2019. The months included are January, February, June, July, August, and December.
The data includes:

* Trip Duration (seconds)
* Start Time and Date
* Stop Time and Date
* Start Station Name
* End Station Name
* Station ID
* Station Latitude/Longitude
* Bike ID
* User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
* Gender (0=unknown; 1=male; 2=female)
* Year of Birth

Data notes:
This data has been processed to remove trips that are taken by staff as they service and inspect the system, trips that are taken to/from any of our “test” stations (which we were being used more in June and July 2013), and any trips that were below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it's secure).
* Trip count and mileage estimates include trips with a duration of greater than one minute.
* Mileage estimates are calculated using an assumed speed of 7.456 miles per hour, up to two hours. Trips over two hours max-out at 14.9 miles. Once you opt into Ride Insights, the Citi Bike app will use your phone's location to record the route you take between your starting and ending Citi Bike station to give exact mileage.
* The data only includes trips that begin at publicly available stations (thereby excluding trips that originate at our depots for rebalancing or maintenance purposes).