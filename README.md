# Pathfinder

An interactive visualizer for graph search algorithms- watch BFS, DFS, Dijkstra's, and A* navigate a live grid in real time.

🗺️ **[Try it live →](https://pathfinderbydeepanshi.vercel.app)**

---

## Algorithms

| Algorithm | Guarantees shortest path | Weighted edges |
|---|---|---|
| BFS | ✅ (unweighted) | ❌ |
| DFS | ❌ | ❌ |
| Dijkstra's | ✅ | ✅ |
| A\* | ✅ | ✅ |

A* uses Manhattan distance as the heuristic — optimal for grid movement without diagonals.

## Features

- Draw walls by clicking/dragging on the grid
- Drag start and end nodes to reposition
- Visualizes the exploration frontier in real time
- Shows the final shortest path after search completes
- Clear board or reset only walls without losing node positions

## Stack

React, TypeScript- no external visualization libraries. All grid logic and animation written from scratch.

## Running locally

```bash
git clone https://github.com/deepanshiruhil/pathfinder.git
cd pathfinder
npm install
npm start
```

---

Built by [Deepanshi Ruhil](https://github.com/deepanshiruhil)
