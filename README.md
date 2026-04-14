# Algorithm Strategies Mini-Project

## Problem Context

Real-world systems require efficient decision-making and optimization. This project implements and compares different algorithmic paradigms (Divide & Conquer, Greedy, Dynamic Programming, and Brute Force) to understand their scalability, time complexity, and practical performance trade-offs.

## Algorithmic Strategies Implemented

1. **Divide and Conquer:** Merge Sort ($O(n \log n)$) - Used for efficient large-scale sorting.
2. **Brute Force:** Insertion Sort ($O(n^2)$) - Used as a baseline to demonstrate exponential growth in complexity.
3. **Greedy:** Fractional Knapsack ($O(n \log n)$) - Makes locally optimal choices to maximize value based on value-to-weight ratios.
4. **Dynamic Programming:** 0/1 Knapsack ($O(nW)$) - Solves overlapping subproblems to find the absolute optimal packing without breaking items.

## Setup Instructions

1. Clone this repository.
2. Create a virtual environment: `python -m venv .venv`
3. Activate the environment:
   - Windows: `.venv\Scripts\activate`
   - Mac/Linux: `source .venv/bin/activate`
4. Install dependencies: `pip install matplotlib numpy memory_profiler jupyterlab`

## Usage

1. Launch Jupyter Lab: `jupyter lab`
2. Navigate to `notebooks/algo_strategies_notebook.ipynb`.
3. Run the "Profiling & Visualization Engine" cell to generate the performance comparison graphs.
