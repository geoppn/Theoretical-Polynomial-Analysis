# Theoretical Polynomial Analysis

Γεώργιος Παπαϊωαννου - 1115202100222

## Overview

This project explores fundamental topics in computational geometry and linear programming. Using Python and Jupyter Notebook, it provides implementations and visualizations for algorithms such as convex hull finding, linear programming, Voronoi diagrams, Delaunay triangulation, and geometric range searching.

## Contents

### 1. Convex Hull Algorithms

Implemented and compared the following algorithms:
- **Incremental Algorithm:** Builds the convex hull by adding points one at a time.
- **Gift Wrapping (Jarvis March):** Finds the convex hull by “wrapping” around the outer points.
- **Divide and Conquer:** Splits the point set and merges hulls recursively.
- **QuickHull:** Efficiently partitions points to quickly construct the hull.

All algorithms were applied to 120 random points, with results visualized. Performance and results are compared.

### 2. Algorithm Runtime Comparison

Benchmarked the above convex hull algorithms across varying point set sizes (100, 500, 1000, 5000, 10000). Results are presented in a table, showing the execution time for each.

### 3. Linear Programming

- Implemented an incremental algorithm for solving LP problems using `scipy.optimize.linprog`.
- Solved a specific LP instance, plotted the feasible region, and

### 3. Linear Programming

- Implemented an incremental algorithm for solving LP problems using `scipy.optimize.linprog`.
- Solved a specific LP instance, plotted the feasible region, and visualized the optimal solution.

### 4. Voronoi Diagram & Delaunay Triangulation

- Used `scipy.spatial` to generate and visualize the Delaunay triangulation and Voronoi diagram for randomly chosen points.
- Demonstrated the correspondence between the two structures.

### 5. Geometric Range Search

- Constructed a range tree for efficient 2D orthogonal range queries.
- Visualized the range tree construction step-by-step for small point sets.
- Applied the range query to 120 random points, visualized which points fell inside a given rectangle.

## Visualizations

- Matplotlib plots for convex hulls, feasible regions, Voronoi and Delaunay diagrams, and range trees.
- Step diagrams for the range tree construction (see referenced images `STEP1.png`, `STEP2.png`).

## Complexity Analysis

- Discussed theoretical time complexities for each algorithm.
- Provided notes on how increasing the number of points impacts performance.

## File Structure

- `ergasia.ipynb`: Main notebook with code, explanations, and results.
- `STEP1.png`, `STEP2.png`: Images for range tree construction (within notebook aswell)

