# Day-57 (09 October 2026)

## Problem Statement
Write a program to take an array arr[] of integers as input, the task is to find the previous greater element for each element of the array in order of their appearance in the array. Previous greater element of an element in the array is the nearest element on the left which is greater than the current element. If there does not exist next greater of current element, then previous greater element for current element is -1.

N.B:
- Print the output for each element in a comma separated fashion.
- Do not use Stack, use brute force approach (nested loop) to solve.

### Sample Test Cases
```text
Input:  arr = [1, 3, 2, 4]
Output: -1, -1, 3, -1
```
```text
Input:  arr = [6, 8, 0, 1, 3]
Output: -1, -1, 8, 8, 8
```
```text
Input:  arr = [1, 2, 3, 5]
Output: -1, -1, -1, -1
```
```text
Input:  arr = [5, 4, 3, 1]
Output: -1, 5, 4, 3
```
