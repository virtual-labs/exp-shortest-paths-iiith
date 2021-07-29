1. Consider an example graph of 10 vertices and 15 edges. Pick a source vertex s, and using Dijkstra's algorithm find the shortest path from s to all other vertices.  
2. Dijkstra's algorithm requires that no edge weight is negative. Why is this restriction required? At what place does the algorithm fail if this restriction is removed? Can you create an example graph with one edge of negative weight where Dijkstra's algorithm fails?  
3. Suppose that the edge weights in a graph are all either 1 or 2. Can you modify Dijkstra's algorithm to run faster? If so, describe your approach and analyze the runtime of your approach.  
4. Generalize the above question where the edge weights are between 1 and W.  
5. Is it ture that in any graph there exists an ordering of the vertices as v1, v2, ..., vn, so that when relaxing the edges with one end point being vi in the ith iteration, shortest paths from v1 to all other vertices can be found in a total time of O(m+n)? If so, how can one find such an ordering? You can assume that the graph has no edges of negative weight.  
6. Consider the setting of the above question. How does Dijkstra's algorithm find this sequence?  
7. If G is a directed acyclic graph, is finding the above sequence any easier then applying Dijkstra's algorithm? If so, how?


