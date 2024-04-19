# CVRP
One of my internship projects at the Parsian Center for Quality and Productivity Research involved working on the Capacitated Vehicle Routing Problem (CVRP) to plan the service of a company. Our problem included 17 drivers, two of whom were located at separate coordinates, and 41 employees distributed across the cities of Karaj, Hashtgerd, Abiek, and Qazvin. Using the geographical coordinates and OpenStreetMap API, I calculated the distance and time between each pair of employees and stored the data in the "Routing problem - Raw Data - V2.xlsx" file. The code for these calculations is available in the "Time Matrix Calculation.ipynb" file. Due to privacy concerns, the names of the employees and drivers have been changed.

We used [Google OR-Tools](https://developers.google.com/optimization/routing/cvrp) library in Python to solve this optimization problem and arrived at the following solution for each driver. In total, it was determined that only 10 drivers are needed, and the total time traveled by all drivers is 785 minutes.

We have also utilized the [folium library](https://python-visualization.github.io/folium/latest/), which is a powerful library for creating maps, for visualization. Initially, we plotted a map named "Location of individuals" to display the location of each individual. Additionally, we created 10 maps to illustrate the routes and the individuals assigned to each of the 10 drivers.

<iframe src="locations of individuals.html" width="100%" height="300px"></iframe>
<iframe src="map0.html" width="100%" height="300px"></iframe>
<iframe src="map1.html" width="100%" height="300px"></iframe>
<iframe src="map2.html" width="100%" height="300px"></iframe>
<iframe src="map3.html" width="100%" height="300px"></iframe>
<iframe src="map4.html" width="100%" height="300px"></iframe>
<iframe src="map5.html" width="100%" height="300px"></iframe>
<iframe src="map6.html" width="100%" height="300px"></iframe>
<iframe src="map7.html" width="100%" height="300px"></iframe>
<iframe src="map8.html" width="100%" height="300px"></iframe>
<iframe src="map9.html" width="100%" height="300px"></iframe>

