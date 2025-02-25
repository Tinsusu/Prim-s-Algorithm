## Prim's Algorithm for Electricity Grid Implementation in Denmark

### Overview

This project implements Prim's Algorithm to determine the shortest path for constructing an efficient electricity grid in Denmark. A Min-Heap (Priority Queue) is utilized to sort and select the shortest path efficiently.

### Why Prim's Algorithm?

Minimizes Total Cost: Finds the shortest path to connect all power stations with minimal wiring costs.

Avoids Cycles: Ensures efficient distribution without redundant connections.

Optimal for Dense Graphs: Suitable for modeling Denmark’s power grid, where cities and substations are well connected.

### Algorithm Explanation

Prim’s algorithm starts with a single node and iteratively expands the Minimum Spanning Tree (MST) by adding the nearest unvisited node:

Choose an arbitrary starting node.

Use a Min-Heap (Priority Queue) to select the edge with the smallest weight that connects a visited node to an unvisited node.

Add the selected edge to the MST.

Repeat steps 2-3 until all nodes are included.

### Implementation Steps

Graph Representation: Represent Denmark’s cities and substations as nodes and the possible power lines as weighted edges.

Priority Queue (Min-Heap): Use a Min-Heap to always select the smallest available edge efficiently.

Tracking MST: Maintain a set of visited nodes to avoid cycles.

Edge Selection: At each step, choose the lowest-cost connection to an unvisited node using the Min-Heap.

Completion: The process stops when all nodes are connected, forming the MST.

### Technologies Used

Java: Core programming language for implementation.

Graph Data Structure: Representing Denmark’s electricity grid.

Priority Queue (Min-Heap): Efficient edge selection.
