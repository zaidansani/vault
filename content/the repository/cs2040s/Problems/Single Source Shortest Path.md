---
publish: true
title: Single Source Shortest Path
---
> [!summary] Finding the shortest path between a pair of vertices.

| Condition                 | Algorithm                                               | Time Complexity |
| ------------------------- | ------------------------------------------------------- | --------------- |
| Unweighted Graph          | BFS                                                     | $O(V + E)$      |
| No Negative Weight Cycles | [Bellman-Ford](../Algorithms/Bellman-Ford.md)           | $O(VE)$         |
| No Negative Weights       | [Dijkstra's](../Algorithms/Dijkstra's.md)               | depends..       |
| Tree                      | BFS/DFS                                                 | $O(V)$          |
| Directed Acyclic Graph    | [Topological Sort](../Algorithms/Topological%20Sort.md) | $O(V + E)$      |
