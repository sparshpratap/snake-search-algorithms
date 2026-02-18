# Search Algorithms for Snake Game

This project implements classical search algorithms to control a Snake agent in a grid-based game environment.
At each step, the agent computes a complete path to the food and executes it sequentially.

The project was developed as part of an Artificial Intelligence fundamentals coursework.

---

## Problem Description

The Snake game is modified to include:
- Static obstacles that should be avoided
- Tiles that reduce the snake’s score and length

The AI agent must:
- Find a valid path to the food
- Avoid obstacles and its own body
- Recompute a path whenever the current one is exhausted or invalid

---

## Implemented Algorithms

The following search algorithms are implemented and can be executed independently:

- **Breadth-First Search (BFS)**
- **Depth-First Search (DFS)**
- **Dijkstra’s Algorithm**
- **A\* Search**

---

## Key Features

- Grid-based state representation
- Cost-aware pathfinding
- Manhattan-distance heuristic for A*
- Visualization of visited nodes
- Automatic replanning when no path is available

---

## Cost Function

- Each move has a base cost of 1
- Penalty is added to discourage moving into undesirable tiles
- Dijkstra and A* use accumulated path cost for decision making

---

## Technologies Used

- Python
- Pygame

