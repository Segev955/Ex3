# Ex3 Directed Weighted Graphs Algorithms
python

In this assignment we constructed directed weighted graphs and implemented on them various algorithms including famous algorithm's. The algorithms include the Traveler Salesman Problem,BFS, Dijkstra's algorithm and more.
## Our research:
this assignment was done after doing more or less the same assignment in java. 
Before that assignment we read about directed weighted graph and algorithm's that can be used on them.
the BFS algorithm was necessary at the project-
In case of wanting to run on a graph we to rely on the BFS algorithm :<br>
BFS:<br>https://en.wikipedia.org/wiki/Breadth-first_search <br>
in addition,a very useful algorithm that we already met in other courses like System Programming and Algorithms part 1 for directed weighted graphs is Dijkstra's Algorithms <br>
https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm <br>

## The body of the assignment
The assignment implementation included two main classes:
<br>*DIGRAPH-Creating a representation of a directed weighted graph. that was done by creating a class for the graph which included a annnonymus class for  Node.
<br>*GRAPHALGO -implimentation of different algorithms that can be used on a graph of that sort. the algorithms included an option to extract a representation of a graph from a json file and updating the right fields, plotting the graph - creating a visual representation of the graph , and different mathematical algorithms as those that were mentioned before. furthermore on the algorithms:
## Directed Weighted Graph Algorithms

 The algorithms that can be used on a directed weighted graph:<br>

-**shortestPath**: This function computes the shortest path and returns a list of vertices representing the path and the weight from source to destination - the sum of all the edges in the path.
To implement this function we used Dijkstra's algorithms to compute all the shortest distances from a source vertex to any vertex on the graph.
Then after using Dijkstra's algorithms on a copy of the graph we ran back from the destination back to the source while computing the sum of each edge from destination to source.

-**center**: This function finds the center of the graph: https://en.wikipedia.org/wiki/Graph_center <br>
we used Floyd-Warshall algorithm to find the center of the graph. <br>
https://en.wikipedia.org/wiki/Floyd%E2%80%93Warshall_algorithm <br>

-**tsp**: Travelling salesman problem- in this function we made a function that computes a route for the travelling salesman.
the function cumputes shortest path from each one of the given nodes to another given node. once done, we check for the shortest path we computed. <br>
https://en.wikipedia.org/wiki/Travelling_salesman_problem <br>


## UML
![image](https://user-images.githubusercontent.com/93653029/147587124-d316cfef-7a19-4184-b701-b3e8326a2e7c.png)


## Algorithms running times
running times, including a comparison to the previous java project can be found in the wiki added to this github project.
https://github.com/Segev955/Ex3/wiki
## Running The Program
To run the program open the command prompt in the folder that contains it and type "python main.py ../data/G1.json" (or any other file) like in the picture bellow.<br>
![image](https://user-images.githubusercontent.com/93653029/147609275-ff988547-e015-45d8-a675-ce210195e81b.png)

result checks provided these visuals:<br>
check1

![image](https://user-images.githubusercontent.com/93653029/147585208-85c6ea43-5396-4ae1-b4f6-effcc5017b31.png)


<br>check2<br>
![image](https://user-images.githubusercontent.com/93653029/147585281-27a52a17-b997-4e09-adee-5a0bcf9376a3.png)


