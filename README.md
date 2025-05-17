# N-Puzzle Solver 🧩

This project provides a solver for the classical **N-Puzzle problem** (such as 8-puzzle, 15-puzzle, etc.), using search algorithms and heuristic functions. It also includes a simple GUI for interaction.

## 📌 Overview

The N-Puzzle is a sliding puzzle consisting of numbered tiles on a board with one tile missing. The goal is to rearrange the tiles to achieve a target configuration by sliding tiles into the empty space.

In this project:
- The empty space is represented by `0`.
- Heuristics such as **Manhattan Distance** and **Misplaced Tiles** are used to guide the search.
- A GUI interface allows users to input the puzzle and see the steps to solve it.

## 🚀 Features

- Supports any N-puzzle size (e.g. 8-puzzle, 15-puzzle)
- Implements classical search algorithms
- Uses admissible heuristics for efficient solving
- Visualizes the steps via GUI

## 🛠️ Technologies Used

- **Python**
- **Tkinter** for GUI
- **Search algorithms** (A*, etc.)
- **Heuristics**: Manhattan Distance, Misplaced Tiles

## 💡 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/HagerEssam12/N-Puzzle-Solver.git
   cd N-Puzzle-Solver
