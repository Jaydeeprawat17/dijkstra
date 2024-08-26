# Dijkstra

Dijkstra is a C++ implementation of Dijkstra's algorithm, which finds the shortest paths between nodes in a graph. This implementation allows for both directed and undirected graphs and is capable of handling graphs with various vertices and weighted edges.

## Features

- Supports both directed and undirected graphs.
- Uses Dijkstra's algorithm to find the shortest path from a source vertex to all other vertices.
- Handles weighted edges.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., Turbo C++, GCC).
- A terminal or command prompt to compile and run the program.

### Installation

1. **Clone the repository** (if using version control):

   ```bash
   git clone https://github.com/yourusername/Dijkstra.git
   cd Dijkstra
   ```

### Example
**Input**

   ```bash
    Is the graph directed? (1 for Yes, 0 for No): 0
    Enter the number of edges: 5
    Enter vertex1, vertex2, and weight for each edge:
    1: A B 4
    2: A C 2
    3: B C 5
    4: B D 10
    5: C D 3
    Enter source vertex: A
   ```

**Output**

   ```bash
 RESULT SET:
   A 0
   B 4
   C 2
   D 5
PI:
   A 0 
   B A 4
   C A 2
   D C 5
   ```
### Code Explanation
**The code is structured around the Dijkstra class, which handles the graph data and implements Dijkstra's algorithm. The key methods include:**
   ```bash
   initialize_graph(): Initializes the graph with user input.
   DIJKSTRA(): Runs Dijkstra's algorithm to compute the shortest paths.
   extract_min(): Finds the vertex with the minimum distance.
   relex(): Updates the shortest path estimates.
   show(): Displays the result set and shortest paths.
  ```
