# Maze Pathfinding: IDDFS vs. Best First Search

This project explores the efficiency of **Blind Search** vs. **Informed Search** algorithms in a randomized 6x6 grid environment.

## Features
* **Randomized Setup:** Generates random start/goal positions and barriers per coursework constraints.
* **IDDFS:** Implements Iterative Deepening Depth-First Search to find the shortest path with minimal memory.
* **Best First Search:** Utilizes a **Manhattan Distance** heuristic to optimize goal-seeking.
* **Visualization:** Full grid rendering using `Matplotlib`.

## Performance Comparison
| Metric | IDDFS | Best First Search |
| :--- | :--- | :--- |
| **Strategy** | Level-by-level (Blind) | Heuristic-guided (Informed) |
| **Shortest Path** | Guaranteed | Usually finds it efficiently |
| **Efficiency** | Lower (Re-visits nodes) | Higher (Aims for goal) |

## Requirements
* Python 3.x
* Matplotlib
* Heapq (Standard Library)
