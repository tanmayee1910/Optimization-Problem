# Optimization-Problem
Optimizing Data Packet Routing Paths for Airplanes over North Atlantic
## Problem Statement: -
The given problem consists of data of 216 airplanes flying over North Atlantic. We are given two Ground Stations Heathrow (LHR) and Newark Liberty International Airport (EWR). In order to
provide Internet access to passengers onboard, each airplane needs to find an optimal data packet routing path to a ground station (GS) in terms of one or two and more objectives to be
optimized. For finding the optimum path between each airplane, Genetic Search Algorithm and Particle Swarm is implemented. Given a set of airplanes and a set of ground stations,
1) Find a routing path for each airplane that can access any of the ground stations such that the end-to-end data transmission rate is maximized.
2) Find a routing path for each airplane that has the maximum end-to-end data transmission rate and the minimum end-to-end latency.
## Dataset Description: -
The given dataset contains the data of 216 flights flying over North Atlantic. There are five columns and 149 rows in the dataset. The columns in the dataset are: -
1. Flight Number: - Each flight is assigned unique flight number.
2. Time Stamp: - A flight timestamp is the time at which a flight departs or arrives. In this dataset is UTC time 13:00 of Jun 29th, 2018.
3. Altitude: - Vertical distance from the measurement location to mean sea level. Altitude in this dataset is given feet.
4. Longitude: - Longitude is a geographic coordinate that specifies the east-west position of a point on the Earth's surface. It is an angular measurement, usually expressed in degrees,
minutes, and seconds, and is traditionally measured from the Prime Meridian. Longitude is given in degree.
5. Latitude : - Latitude is a geographic coordinate that specifies a location's distance north or south of the Earth's equatorial plane. Latitude is given in degree.
## Conclusion: - 
After observing the fitness function, it can be seen that PSO is giving better results. Both PSO and the Genetic Algorithm have higher transmission rates. The Greedy
Algorithm has the lowest latency rate. The Genetic Algorithm took more time to execute compared to PSO, but the Greedy Algorithm is obviously faster because it
has no loops.
