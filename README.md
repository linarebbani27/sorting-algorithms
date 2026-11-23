Sorting Algorithms: Implementation, Performance Measurement and Comparison

1. Project Overview

This project implements and compares five popular sorting algorithms using Python. It aims to study their performance in terms of execution time and memory usage for different input sizes.

The main objective is to understand how each sorting algorithm behaves and compare its efficiency under different conditions.

2. Implemented Algorithms

The following sorting algorithms are implemented from scratch:

Bubble Sort: Uses an early-exit flag to stop when the array is already sorted.

Selection Sort: Repeatedly selects the smallest element and places it in the correct position.

Insertion Sort: Builds the sorted array one element at a time.

Merge Sort: Uses the recursive divide-and-conquer approach.

Quick Sort: Uses the partitioning technique with the Median-of-Three pivot strategy.

3. Technologies Used

Programming Language: Python

Python Version: 3.15.2

Libraries:

random – for generating random arrays.

time – for measuring execution time.

tracemalloc – for measuring memory usage.

csv – for exporting benchmark results.

matplotlib – for visualizing performance results.

4. Features

The project includes the following features:

Interactive menu to select a sorting algorithm.

Comparison of all five algorithms.

Different input types:

Random arrays.

Sorted arrays.

Reverse-sorted arrays.

Arrays with duplicate values.

Execution time measurement.

Memory usage measurement.

Repeated benchmark runs to obtain more reliable results.

Exporting results to CSV files.

Graphical visualization of performance comparisons.

Verification that the resulting arrays are correctly sorted.

5. Algorithm Complexity Comparison

Algorithm

Best Case

Average Case

Worst Case

Bubble Sort

O(n)

O(n²)

O(n²)

Selection Sort

O(n²)

O(n²)

O(n²)

Insertion Sort

O(n)

O(n²)

O(n²)

Merge Sort

O(n log n)

O(n log n)

O(n log n)

Quick Sort

O(n log n)

O(n log n)

O(n²)

6. How to Run the Project

Make sure Python is installed on your computer.

Run the program using the following command:

py main.py

The interactive menu will allow the user to choose an algorithm, generate input data, run comparisons, and view performance measurements.

7. Benchmark Methodology

To evaluate the performance of the sorting algorithms, different input sizes are used:

1,000 elements

5,000 elements

10,000 elements

50,000 elements

100,000 elements

The benchmark uses randomly generated data with a fixed seed to ensure reproducibility.

Each algorithm is executed multiple times (for example, 5 runs), and the average execution time is calculated.

All algorithms receive copies of the same input array to ensure a fair comparison.

For large input sizes, quadratic algorithms may be skipped to avoid excessive execution time.

8. Results and Analysis

The performance results are analyzed based on execution time and memory usage.

The comparison helps identify the most efficient algorithms for different input sizes and understand the impact of algorithmic complexity on performance.

The results are presented using tables and graphs to make the comparison clearer.

Actual benchmark results and graphs will be added after running the experiments.

9. Project Information

Author: Rebbani Lina

Group: Group 1

Department: Computer Science and automation

Module: Algorithms and Data Structures

Academic Year: 2026–2027

Instructor: Dr. Sabri Ghazi

10. Conclusion

This project provides a practical comparison of five sorting algorithms and demonstrates the importance of algorithmic complexity in performance evaluation.

By measuring execution time and memory usage, it helps understand the advantages and limitations of each algorithm and highlights how the choice of sorting algorithm can affect efficiency when working with different input sizes.
