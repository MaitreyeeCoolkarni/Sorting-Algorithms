# Sorting-Algorithms

# 📘 Sorting Algorithms in C++

---

## Algorithms

### Bubble Sort Algorithm
1. Start with an array of `n` elements.  
2. Repeat `n-1` passes.  
3. In each pass, compare adjacent elements:  
   - If `array[j] > array[j+1]`, swap them.  
4. After each pass, the largest element moves to the end.  
5. Continue until the array is sorted.  

---

### Quick Sort Algorithm
1. Choose a **pivot element** (commonly the last element).  
2. Partition the array such that:  
   - All elements smaller than pivot are placed to its left.  
   - All elements greater than pivot are placed to its right.  
3. Recursively apply QuickSort to the left and right partitions.  
4. Base case: when low >= high, stop recursion.  
5. Combine results to get a fully sorted array.  

---

### Selection Sort Algorithm
1. Start with an unsorted array of `n` elements.  
2. For each index `i` from 0 to n-2:  
   - Find the **minimum element** from the unsorted part of the array.  
   - Swap it with the element at index `i`.  
3. After each iteration, the smallest element is placed in the correct position.  
4. Repeat until the array is sorted.  

---

## Theory of Sorting

Sorting is the process of arranging elements of a list/array in a certain order (usually ascending or descending).  
It is a **fundamental operation in computer science** because sorted data makes searching, merging, and other operations more efficient.  

### Common Sorting Methods:
- **Bubble Sort**: Simple comparison-based algorithm, repeatedly swaps adjacent elements.  
- **Selection Sort**: Repeatedly selects the smallest element from the unsorted portion and places it in order.  
- **Quick Sort**: Divide-and-conquer approach; partitions array based on pivot and sorts recursively.  

### Applications of Sorting:
- Searching (Binary Search requires sorted data).  
- Data organization in databases.  
- Scheduling and task management.  
- Compression and optimization techniques.  

## Conclusion

- Sorting algorithms differ in efficiency, complexity, and use cases.  
- **Bubble Sort** is simple but inefficient for large datasets (O(n²)).  
- **Selection Sort** reduces swaps but still has O(n²) comparisons.  
- **Quick Sort** is much faster on average (O(n log n)) and widely used in practice.  
- Choosing the right sorting algorithm depends on **data size, data distribution, and performance requirements**.  
