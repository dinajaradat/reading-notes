## Graphs are a fundamental data structure used in computer science and other fields to model and represent relationships between entities. They are versatile and powerful tools that allow us to analyze and solve a wide range of problems. Graphs provide a way to capture and visualize complex interconnections and dependencies, making them essential for understanding and solving real-world scenarios. By leveraging graph theory and algorithms, we can tackle problems related to network analysis, social networks, route planning, data organization, and much more. Understanding graphs is crucial for developing efficient solutions to various computational challenges.

## How to traverse the graph ?

## Breadth First : BFS starts at a single vertex and explores all of its adjacent vertices before moving on to the next level of vertices. This process continues until all vertices in the graph have been visited.

## Here is what the algorithm breadth first traversal looks like:

### Enqueue the declared start node into the Queue.
### Create a loop that will run while the node still has nodes present.
### Dequeue the first node from the queue
### if the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.

# Complete vs Connected vs Disconnected
## Links to an external site.Complete Graphs
### A complete graph is when all nodes are connected to all other nodes.

## Links to an external site.Connected
### A connected graph is graph that has all of vertices/nodes have at least one edge.

## Links to an external site.Disconnected
### A disconnected graph is a graph where some vertices may not have edges.