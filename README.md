# Pathfinding-Visualizer

## Overview
Pathfinding Visualizer is an interactive tool that demonstrates the step-by-step execution of pathfinding algorithms. It uses a grid-based system to visualize how various algorithms explore nodes and determine the shortest path between two points.

---

## Features
- **Interactive Grid**:
  - Users can set a start point, end point, and obstacles by clicking on the grid.
  - Easily reset or clear the grid to try new configurations.
- **Algorithms**:
  - **A***: A heuristic-based pathfinding algorithm.
  - **Breadth-First Search (BFS)**: An uninformed search algorithm that explores layer by layer.
  - **Depth-First Search (DFS)**: An uninformed search algorithm that explores as deep as possible.
- **Real-Time Visualization**:
  - Watch the algorithm explore nodes, highlight the visited ones, and find the shortest path.
- **Customizable Grid**:
  - Create different layouts with varying start/end points and barriers.

---

## Purpose
The project serves as an educational tool for:
- Understanding pathfinding algorithms and their efficiency.
- Learning how search algorithms work on graphs.
- Visualizing differences between informed and uninformed search techniques.

---

## Technologies Used
- **Python 3.7+**: Programming language.
- **Pygame**: Used for grid visualization and user interaction.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd pathfinding-visualizer
   ```

3. Install dependencies:
   ```bash
   pip install pygame
   ```

4. Run the application:
   ```bash
   python pathfinding_visualizer.py
   ```

---

## Usage Instructions
1. **Set Start and End Points**:
   - Left-click on any cell to set the **start point** (orange) and the **end point** (turquoise).
2. **Add Barriers**:
   - Left-click to create obstacles (black cells) that the algorithm cannot pass through.
3. **Run Algorithms**:
   - Press `SPACE` to start the selected pathfinding algorithm.
   - The shortest path will be visualized in blue.
4. **Clear the Grid**:
   - Press `C` to reset the grid.

---

## Key Bindings
- **Left Click**: Set start, end, or barriers.
- **Right Click**: Remove barriers or reset points.
- **Spacebar**: Run the algorithm.
- **C Key**: Clear the grid.

---

## Algorithms Explained
### 1. **A***
- Uses a heuristic function (Manhattan distance) to guide the search.
- Guarantees the shortest path.

### 2. **BFS**
- Explores all neighbors layer by layer.
- Guarantees the shortest path in an unweighted grid.

### 3. **DFS**
- Explores as deep as possible before backtracking.
- Does not guarantee the shortest path.


