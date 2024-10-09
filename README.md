# Chinese Postman Problem Solver
This code finds the optimized route for the Chinese Postman Problem, where the objective is to traverse all links in a graph.

**Overview**
If the graph is Eulerian (i.e., all nodes have an even degree), finding the optimal closed loop is straightforward. However, if the graph is not Eulerian, additional steps are required to make it Eulerian.

Algorithm Steps:
* Check for Eulerian Graph: The algorithm first checks if the graph is Eulerian.
* Graph Modification: If the graph is not Eulerian, the algorithm finds the optimized way to modify the graph to make it Eulerian.
* Find Eulerian Path: Once the graph is Eulerian, the algorithm computes the Eulerian path that spans all links.
