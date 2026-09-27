# maze-solver

A C++ console application designed to generate and solve mazes using various pathfinding algorithms. 

## Features
- **Maze Input:** Load mazes from standard preset files, provide a custom file path, or input them manually.
- **Solving Algorithms:**
  - **BFS (Breadth-First Search):** Standard shortest-path finding.
  - **Two-End BFS:** Bidirectional search for faster pathfinding.
  - **Ant Algorithm:** Pathfinding based on ant optimization behavior.
  - **Manual Mode:** Solve the maze yourself interactively.
- **Performance Metrics:** Measures and displays the time taken and the number of steps required to solve the maze.
- **Interactive Console Menu:** Simple keyboard-driven navigation (up/down arrows and Enter).

## Project Structure
- `src/` & `headers/` - C++ source code and header files (Algorithms, Controllers, Views, Data Structures).
- `mazes/` - Preset maze files.
- `test/` - Maze files for testing purposes.

## Requirements
- A C++ compiler (e.g., GCC, MSVC, Clang).
- Operating System with a standard console (uses `<conio.h>` / `<windows.h>` API, suitable for Windows environments).

## Usage
Compile the source code inside the `src/` directory and run the resulting executable. Follow the on-screen instructions to select your maze input method and the desired solving algorithm.
