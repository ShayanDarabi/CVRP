# CVRP
One of my internship projects at [the Parsian Center for Quality and Productivity Research](https://pqprc.ac.ir/) involved working on the Capacitated Vehicle Routing Problem (CVRP) to plan the service of a company. Our problem included 17 drivers, two of whom were located at separate coordinates, and 41 employees distributed across the cities of Karaj, Hashtgerd, Abiek, and Qazvin. Using the geographical coordinates and OpenStreetMap API, I calculated the distance and time between each pair of employees and stored the data in the "Routing problem - Raw Data - V2.xlsx" file. The code for these calculations is available in the "Time Matrix Calculation.ipynb" file. Due to privacy concerns, the names of the employees and drivers have been changed.

I used [Google OR-Tools](https://developers.google.com/optimization/routing/cvrp) library in Python to solve this optimization problem and arrived at the following solution for each driver. In total, it was determined that only 10 drivers are needed, and the total time traveled by all drivers is 785 minutes.

<img src="https://github.com/ShayanDarabi/CVRP/blob/main/img/Solution_part1.jpg" alt="Alt Text" width="600" height="500">
<img src="https://github.com/ShayanDarabi/CVRP/blob/main/img/Solution_part2.jpg" alt="Alt Text" width="400" height="400">
<img src="https://github.com/ShayanDarabi/CVRP/blob/main/img/Solution_part3.jpg" alt="Alt Text" width="600" height="500">


I have also utilized the [folium library](https://python-visualization.github.io/folium/latest/), which is a powerful library for creating maps, for visualization. Initially, I plotted a map named "Location of individuals" to display the location of each individual. Additionally, I created 10 maps to illustrate the routes and the individuals assigned to each of the 10 drivers. All the maps have been uploaded to the docs directory.




