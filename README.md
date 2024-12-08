# Sorting Algorithms: Insertion, Merge, and Kruskal's

## Overview

This repository contains a detailed implementation of three fundamental algorithms used in computer science: **Insertion Sort**, **Merge Sort**, and **Kruskal's Algorithm**. These algorithms are essential for sorting data and are widely used in various applications.

The notebook in this repository demonstrates the working of these algorithms with visualizations and explanations.


## About the Project

This project focuses on implementing and explaining three sorting algorithms:

1. **Insertion Sort**: A simple and efficient sorting algorithm that builds the final sorted array one item at a time. It works similarly to how one might sort playing cards in their hands.
  
2. **Merge Sort**: A divide-and-conquer algorithm that divides the array into two halves, sorts them recursively, and then merges them into a single sorted array.
   
3. **Kruskal's Algorithm**: A graph algorithm used for finding the Minimum Spanning Tree (MST) of a graph. This algorithm helps in efficiently connecting all the nodes in the graph with the minimum cost.

### Key Concepts Covered:

- **Sorting Algorithms**: Insertion Sort, Merge Sort
- **Graph Algorithms**: Kruskal's Algorithm for Minimum Spanning Tree (MST)

## Algorithms Overview

### 1. Insertion Sort
Insertion sort works by building a sorted section of the list one element at a time by repeatedly inserting elements into the correct position in a sorted subset.

**Time Complexity**:
- Best: O(n)
- Average: O(n^2)
- Worst: O(n^2)

### 2. Merge Sort
Merge Sort is a recursive algorithm that splits an array into halves, recursively sorts each half, and then merges them back together. It is much faster than Insertion Sort, especially for large datasets.

**Time Complexity**:
- Best: O(n log n)
- Average: O(n log n)
- Worst: O(n log n)

### 3. Kruskal's Algorithm
Kruskal’s algorithm is used to find the Minimum Spanning Tree (MST) of a graph. It selects the edges of the graph in increasing order of weight, ensuring that no cycles are formed.

**Time Complexity**:
- Best: O(E log E), where E is the number of edges in the graph.

## How to Run the Notebook

1. Clone this repository to your local machine or open the notebook directly from GitHub.
2. Open the notebook (`Sorting Algorithms (Insertion-Merge-Kruskal).ipynb`) using Jupyter Notebook, JupyterLab, or any other compatible environment like Google Colab.
3. Run each cell to execute the algorithms and observe the results.


