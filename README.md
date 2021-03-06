# Route-Planner
🛣️Route-Planner
A data structures course semester project made using Dijkstra Algorithm, DFS algorithm, Graphs and LinkedList.

🔍OverView
ROUTE-PLANNER-- Semester Project for Data Structures Course offered at National University Of Science and Technology(NUST).
In this project we were asked to utilize our knowledge of data structures and algorithm to devise a program that can calculate shortest path between cities and even inside city. The main requirements of Project are as follow:

Map the shortest route between two cities to Pakistan(major cities)
Map shortest route between two towns inside each city.
There should be option to map shortest route with respect to either time or with respect to distance.
Make code as efficient as possible.
⚡Code Structure
The code is structured in such a way that each city is a single node of a tree which is itself capable of holding an entire tree for its towns. Each node is linked to another node and an adjacency list is maintained for all nodes. The program takes starting point and ending point and utilizing Dijkstra algorithm calculates the shortest route between two cities.

For mapping the shortest route between two towns of a city, first identify the city and then pass starting and ending town names. If there exist any path between those two towns, the program will show it.

For finding optimal path with respect to either time or distance, a parameter is passed. Optimal route with respect to either is then displayed.

📚 Data Set
The data set taken for this project is approximatation of google map distance and time between two locations. Data is arranged in columns and each row is taken at once by the program.
Large data set is not maintained. Only major cities data is fed to program. For towns, only lahore and rawalpindi data set is maintained.

👉Usage
When the program runs, following menu pops up with multiple instructions.

image

First of all data set should be fed to program to start processing. So the first step should be to press 2 to load cities data. After doing this, major cities are added but still there is no connection between different cities. To connect cities, edges should be added. Therefore next should be press 3 to load cities edges. At this stage you are ready enough to map shortest route between cities of data set as shown below:


Now in a similar fashion, load the data for towns and then add edges between towns to get program work properly. The following snippet shows shortest route calculation between different towns of lahore.
