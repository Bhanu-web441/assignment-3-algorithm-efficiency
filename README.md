# assignment-3-algorithm-efficiency
Python implementation and analysis of Randomized Quicksort and Hashing with Chaining. Visibility: Public, unless your instructor requires a private repository.

# Assignment 3: Algorithm Efficiency and Scalability

## Overview
This project implements and analyzes Randomized Quicksort,
Deterministic Quicksort, and Hashing with Chaining.

## Requirements
Python 3
Matplotlib

## How to Run
1. Download algorithms.py.
2. Open it in Google Colab or run it using Python 3.
3. Execute the program.
4. Review the benchmark results and graphs.

## Algorithms
Randomized Quicksort selects pivots uniformly at random.
Deterministic Quicksort uses the first element as its pivot.
The hash table uses chaining and dynamic resizing.

## Complexity
Randomized Quicksort:
Expected time: O(n log n)
Worst-case time: O(n²)

Hashing with Chaining:
Expected insert, search, and delete: O(1)
with a bounded load factor and uniform hashing.

## Experimental Analysis
The benchmark compares both sorting algorithms using
random, sorted, reverse-sorted, and repeated-value arrays.

See the report and benchmark_results.csv for findings.
