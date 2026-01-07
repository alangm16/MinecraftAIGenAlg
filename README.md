# Intelligent Agent with Genetic Map Generation
**Pathfinding Agent using A* Algorithm and Genetic Algorithms for Map Generation**

This project is a web-based intelligent agent developed with **HTML, CSS, and JavaScript** that combines the **A\*** pathfinding algorithm with **Genetic Algorithms** to automatically generate optimized maps and environments.

The system generates maps procedurally using evolutionary techniques and then allows an intelligent agent to search for the optimal path between a start and goal position.

---

## Features

- Intelligent agent using the A* search algorithm.
- Procedural map generation using Genetic Algorithms.
- Fitness evaluation of generated maps.
- Interactive grid visualization.
- Configurable start and goal nodes.
- Obstacle generation and evolution.
- Real-time visualization of the search process.
- Runs entirely in the browser (no backend required).

---

## How Genetic Map Generation Works

1. A population of random maps is generated.
2. Each map is evaluated using a fitness function (e.g., solvability, path length, obstacle distribution).
3. Selection chooses the best-performing maps.
4. Crossover and mutation generate new map populations.
5. The process iterates until an optimal or acceptable map is produced.
6. The final map is used by the A* agent for pathfinding.

---

## How the A* Algorithm Works

The A* algorithm uses the following cost function:

f(n) = g(n) + h(n)


Where:
- **g(n)** → Actual cost from the start node to the current node.
- **h(n)** → Heuristic estimate to the goal.
- **f(n)** → Total estimated cost.

The agent always expands the most promising node first to guarantee optimality when using an admissible heuristic.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- A* Pathfinding Algorithm
- Genetic Algorithms
- Data Visualization in Browser

---

By: AlanGM16
