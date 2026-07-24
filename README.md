# Sorting Visualizer

A web-based sorting algorithm visualizer that animates how different sorting algorithms work in real time, with live complexity info and sound feedback.

## Live Demo
[Click here to view](https://pratyaypal54-ops.github.io/sorting-visualizer/)

## Algorithms Included

| Algorithm      | Best       | Average    | Worst      | Space    | Stable |
|----------------|------------|------------|------------|----------|--------|
| Bubble Sort    | O(n)       | O(n²)      | O(n²)      | O(1)     | Yes    |
| Selection Sort | O(n²)      | O(n²)      | O(n²)      | O(1)     | No     |
| Insertion Sort | O(n)       | O(n²)      | O(n²)      | O(1)     | Yes    |
| Merge Sort     | O(n log n) | O(n log n) | O(n log n) | O(n)     | Yes    |
| Quick Sort     | O(n log n) | O(n log n) | O(n²)      | O(log n) | No     |

## Features

- Time and space complexity card that updates live when you switch algorithm
- Array type selector — Random, Reversed, Nearly Sorted, Few Unique
- Sound feedback using Web Audio API with no external library
- Value labels on bars for small arrays of 15 elements or fewer
- Spacebar shortcut to start and stop sorting
- Adjustable array size from 6 to 40 elements
- Speed control — Slow, Normal, Fast
- Live stats — comparisons, swaps, and time elapsed
- Color coded bars — comparing, swapping, sorted, pivot

## How to Run

Just open `index.html` in any browser. No installation needed.

## Tech Stack

HTML | CSS | JavaScript | Web Audio API
