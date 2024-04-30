# CMPS 2200 Recitation 10## Answers

**Name:** Julia Renner


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**

- The work of reachable assuming n nodes and m edges is O(m+n).

- **4)**

- The worst case number of times reachable would need to be called is 1 because when it is called it traverses the entire graph, and if it does not reach each node in this process then the graph is confirmed not connected.

- **5)**

- The Work of connected assuming n nodes and m edges is O(n+m)

- **7)**

- The work of reachable would change if the graph representation is an adjacency matrix because it would need to check each whole row in the matrix to find the nodes that connect to the current, so the work would increase to account for the search per node for every node: O(n^2)


