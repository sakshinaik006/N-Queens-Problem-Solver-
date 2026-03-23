# N-Queens-Problem-Solver

A Java implementation of the N-Queens puzzle using a backtracking algorithm to find all valid placements on various board sizes.

## Description
The N-Queens problem involves placing N queens on an NxN chessboard such that no two queens attack each other. This project explores the efficiency of recursive backtracking by measuring the time taken to find all solutions for different values of N.

## Objectives of the Project 

The primary objectives of this project are: 
  - To understand and implement the Backtracking algorithm to solve the N-Queens problem in Java. 
  - To analyze the time and space complexity of the implemented algorithm. 
  - To demonstrate the solution with working Java code and sample outputs. 
  - To study the behavior of the algorithm as N scales upward.

    
## Features
* Recursive backtracking algorithm
* Performance benchmarking for multiple board sizes (N=4 to N=10)
* Formatted solution output for the first three results of each size

## Usage
1. Compile the source code:
   javac NQueens.java
2. Run the application:
   java NQueens

## Complexity Analysis
* Time Complexity: O(N!) - The algorithm explores the search space but prunes branches that violate safety constraints.
* Space Complexity: O(N^2) - The board is represented by a two-dimensional integer array.
