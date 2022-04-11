# Shift-2D-Grid
Python code for Shift 2D Grid problem

## Problem Statement
Given a 2D grid of size m x n and an integer k. You need to shift the grid k times.

In one shift operation:

Element at grid[i][j] moves to grid[i][j + 1].<br>
Element at grid[i][n - 1] moves to grid[i + 1][0].<br>
Element at grid[m - 1][n - 1] moves to grid[0][0].<br>
Return the 2D grid after applying shift operation k times.<br>
