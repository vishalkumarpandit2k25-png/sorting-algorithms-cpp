# Bubble Sort

Bubble Sort is one of the simplest sorting algorithms.  
It sorts an array by repeatedly comparing two adjacent elements and
swapping them if they are in the wrong order.

The algorithm continues this process until the entire array becomes sorted.

---

## Example

Input array:
5 1 4 2 8

After Bubble Sort:
1 2 4 5 8

---

## How Bubble Sort Works

Step 1: Compare the first two elements.  
Step 2: If the first element is greater than the second, swap them.  
Step 3: Move to the next pair of elements.  
Step 4: Repeat this process for the entire array.  
Step 5: After each pass, the largest element moves to the end of the array.

This process continues until the array is completely sorted.

---

## Time Complexity

Best Case: O(n)  
Average Case: O(n²)  
Worst Case: O(n²)

---

## Space Complexity

O(1)

Bubble Sort does not require extra memory.

---

## Implementation

The C++ implementation of Bubble Sort can be found in:

bubble_sort.cpp
