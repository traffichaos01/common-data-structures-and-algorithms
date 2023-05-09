# Graphs
Collections of nodes or values called vertices that might be related; relations between vertices are called edges.

All edges are represented by arrows, arrows represent direction.

O(V+E) S

## Types of Graphs

## Directed Graph
A graph whose edges are directed, meaning that they can only be traversed in one direction, specified by arrow head.

## Undirected Graph
A graph whose edges are undirected, meaning that they can be traversed in both directions.

## Cyclic Graph
A graph that has at least one cycle.
Important to know if graph has a cycle.
A cycle is a path of three or more edges that lead to previously visited vertices.
1 -> 3 -> 5 -> 1

## Acyclic Graph
A graph that has no cycles

## Representation

### Adjacency List
List of nodes in the graph or hash table where key is node in graph, and each node stores list of edges.

## Searching/Traversing
For BFS and DFS
O(V+E) T
O(V) S