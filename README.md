# Dominant-Index-Finder


Problem Statement
Given an integer array nums where the largest element is unique, this function determines whether that element is at least twice as large as every other number in the array. If so, it returns the index of the largest element; otherwise, it returns -1.

Solution Approach
The algorithm follows these steps:
Identify the largest number and its index
Verify dominance condition: Check if the largest number is at least twice as large as all other elements
Return results: Index of dominant number if condition is satisfied, otherwise -1

Key Features
✅ Optimal Time Complexity: O(n) - Processes the array in two passes
✅ Constant Space Complexity: O(1) - Uses minimal extra memory
✅ Clear Logic: Easy-to-understand implementation with meaningful variable names
✅ Edge Case Handling: Properly handles single-element arrays and failure cases
