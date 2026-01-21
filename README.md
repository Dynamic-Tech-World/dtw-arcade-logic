# DTW Arcade Logic 🕹️
**High-performance, logic-driven game engines by Dynamic Tech World.**

[![Game Engine](https://img.shields.io/badge/Logic-Deterministic-orange.svg)](#)
[![Performance](https://img.shields.io/badge/FPS-60_Stable-green.svg)](#)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#license)

This repository serves as a technical showcase for interactive engines built with Vanilla JavaScript and advanced browser APIs. These are not just "games"—they are explorations in **State Management, Pathfinding Algorithms, and Real-time Rendering.**

---

## 🎮 The Game Matrix

| Engine | Technical Highlight | Live Access |
| :--- | :--- | :--- |
| **AI Tic Tac Doom** | Minimax Algorithm (Unbeatable AI) | [Play Now](https://ai-tic-tac-doom.netlify.app/) |
| **Maze Craze** | Procedural Generation & Pathfinding | [Play Now](https://maze-craze-dtw-asset.netlify.app/) |
| **Tetris Engine** | Matrix Rotation & Line Cleansing Logic | [Play Now](https://tetris-game-dtwasset.netlify.app/) |
| **Sudoku** | Constraint Satisfaction Algorithm | [Play Now](https://sudoko-dtw-asset.netlify.app/) |
| **Snake Loop** | Collision Detection & Buffer Management | [Play Now](https://snake-game-loop-dtw-asset.netlify.app/) |
| **Memory Card** | State-Sync & Pattern Matching | [Play Now](https://memory-card-game-dtwasset.netlify.app/) |

---

## 🧠 Engineering Deep-Dive

### 1. Artificial Intelligence (Minimax)
In **AI Tic Tac Doom**, the core engine utilizes a recursive **Minimax algorithm**. The AI evaluates every possible move branch to ensure an "unbeatable" state. This demonstrates advanced tree-traversal and heuristic evaluation logic.

### 2. Procedural Generation
**Maze Craze** utilizes a Depth-First Search (DFS) algorithm to generate perfect mazes. The engine ensures that every generated level is mathematically solvable while maintaining randomized complexity.

### 3. State Machines & Game Loops
For high-speed titles like **Tetris** and **Snake**, I implemented a decoupled game loop. 
- **Deterministic Logic:** Game state updates are independent of the render frame.
- **Collision Detection:** Efficient coordinate-based collision systems built without heavy external libraries.

### 4. Mathematical Complexity
The **Sudoku** engine features a backtracking algorithm for both board generation and validation, ensuring that every puzzle has a unique solution.

---

## 🛠 Tech Stack
- **Engine:** Pure Vanilla JavaScript (ES6+).
- **Rendering:** DOM-optimized manipulation & HTML5 Canvas API.
- **Architecture:** Object-Oriented Programming (OOP) & Functional State management.

---

## 📜 License
**Proprietary Software.**  
Copyright © 2024 Dynamic Tech World.  
All rights reserved. The source code is kept private to protect Intellectual Property. You are free to play and test the live deployments via the links provided.

---
## ☕ Support the Lab
If you appreciate the logic and engineering behind these games, consider supporting our work:
[**Donate via Buy Me a Coffee**](https://buymeacoffee.com/dynamictechworld)
