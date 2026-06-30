# Shortest Path Algorithms Comparison

## Project Overview

This project presents a comparison between two shortest-path algorithms:

- Greedy Best-First Search (GBFS)
- Bellman-Ford Algorithm

The objective is to analyze their performance, efficiency, and suitability for path-finding problems using both theoretical explanations and Python implementations.


## Problem Description

Finding the shortest path between two locations is one of the most important problems in computer science and artificial intelligence.

Shortest-path algorithms are widely used in:

- GPS navigation systems
- Google Maps
- Network routing
- Transportation systems
- Robotics and autonomous vehicles

Since different algorithms have different strengths and weaknesses, selecting the most suitable algorithm can significantly affect performance and accuracy.

## Project Objectives

- Study shortest-path problems.
- Understand how Greedy Best-First Search works.
- Understand how Bellman-Ford works.
- Implement both algorithms using Python.
- Compare their efficiency and performance.
- Analyze their time complexity.
- Provide recommendations based on the results.

---

## Algorithms Included

### 1. Greedy Best-First Search

Greedy Best-First Search selects the node that appears closest to the goal using a heuristic function.

#### Advantages
- Fast execution.
- Simple implementation.
- Suitable for large search spaces.

#### Disadvantages
- Does not always find the optimal path.
- Depends heavily on the heuristic function.


### 2. Bellman-Ford Algorithm

Bellman-Ford calculates the shortest path from a source node to all other nodes by repeatedly relaxing edges.

#### Advantages
- Guarantees the shortest path.
- Handles negative edge weights.
- Detects negative cycles.

#### Disadvantages
- Slower than Greedy Search.
- Higher computational cost.

## Project Structure

```text
ShortestPathAlgorithms/
│
├── greedy_best_first.py
├── bellman_ford.py
├── report.pdf
└── README.md
````


## Technologies Used

* Python 3
* Graph Theory
* Artificial Intelligence Concepts
* Path-Finding Algorithms


## Complexity Analysis

| Algorithm                | Time Complexity |
| ------------------------ | --------------- |
| Greedy Best-First Search | O(E log V)      |
| Bellman-Ford             | O(V × E)        |

Where:

* V = Number of vertices
* E = Number of edges


## Comparison Summary

| Feature                   | Greedy Best-First Search | Bellman-Ford |
| ------------------------- | ------------------------ | ------------ |
| Optimal Path              | No                       | Yes          |
| Speed                     | Faster                   | Slower       |
| Uses Heuristic            | Yes                      | No           |
| Negative Weights          | No                       | Yes          |
| Detect Negative Cycles    | No                       | Yes          |
| Implementation Complexity | Simple                   | Moderate     |


## Conclusion

Greedy Best-First Search provides fast solutions but does not guarantee the shortest path. Bellman-Ford is more reliable because it guarantees optimal results and supports negative edge weights. Therefore, Bellman-Ford is preferred when accuracy is critical, while Greedy Search is suitable when speed is the main concern.



## Author

Wafaa Aluhaidan

and other student 

Information Technology Department

Qassim University

```
```
