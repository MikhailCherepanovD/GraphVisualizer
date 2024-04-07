# GraphVisualizer

QT program for generating and visualizing graphs and a set of algorithms based on them.

## Functions


- **Graph generation**
    - Manually
    - According to the [geometric distribution](https://en.wikipedia.org/wiki/Geometric_distribution)
- **Removing and adding vertices and edges**
    - Manually
    - Using the adjacency matrix
- **Implemented pathfinding algorithms**
    - [Dijkstra](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
    - [Belman-Ford](https://en.wikipedia.org/wiki/Geometric_distribution)
    - [Floyd-Warshall](https://en.wikipedia.org/wiki/Floyd–Warshall_algorithm)
    - Using [BFS](https://en.wikipedia.org/wiki/Breadth-first_search)
- **Implemented pathfinding algorithms**
    - Search for the maximum flow. [The Ford-Fulkerson algorithm](https://en.wikipedia.org/wiki/Ford–Fulkerson_algorithm)
    - [Search for the minimum cost of the stream](https://en.wikipedia.org/wiki/Minimum-cost_flow_problem) using Belman-Ford algorithm.
- **Implemented finding the minimum spanning tree algorithms**
    - [Prim's algorithm](https://en.wikipedia.org/wiki/Prim%27s_algorithm)
    - [Kruskal's algorithm](https://en.wikipedia.org/wiki/Kruskal%27s_algorithm)
- **Other algorithms**
    - [Preufer sequence](https://en.wikipedia.org/wiki/Pr%C3%BCfer_sequence)
    - [Finding an Eulerian cycle](https://en.wikipedia.org/wiki/Eulerian_path)
    - [Finding the Hamiltonian Cycle](https://en.wikipedia.org/wiki/Hamiltonian_path)
    - [Travelling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)




## Building

### Dependecies
- Qt5.x
- QMake 3.x
  
### To run:

- git clone https://github.com/MikhailCherepanovD/GraphVisualizer
- cd GraphVisualizer
- qmake GraphVisualizer.pro
- make
- ./GraphVisualizer
  
### How it works:
![](https://github.com/MikhailCherepanovD/GraphVisualizer/blob/master/gifimage.gif)