# CitiBike_Usage_Analysis

# Problem
The Citibike system in New York City often has a bike imbalance: some stations are empty and others are full. This affects the quality of the service.
## Objective
We use K-means clustering technique to divide the groups of station having similar imbalances at different time
of the year. This will allow to create a rebalancing strategy for the bike sharing operator.

We divided the station groups into 6 groups, clustering using the empty stations along the 24 hours of the day. These vectors are independent and orthogonal which makes it suitable for K-means clustering.

## Results - Visualizations
It can be observed that some groups residential areas are empty in the morning
![image](./Visualizations/empty.gif)
![image](./Visualizations/end.gif)
![image](./Visualizations/start.gif)
