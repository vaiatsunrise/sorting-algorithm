# sorting-algorithm
# Aim: To study different sorting techniques in C++ and implement programs to sort elements of an array.
# Tools: GNU g++ compiler or any online C++ compiler.

# Theory
Sorting is the process of arranging data in a particular order, usually ascending or descending. We have performed ascending. Efficient sorting is crucial in programming as it improves search efficiency and simplifies data processing. Common sorting techniques include Selection Sort, Bubble Sort, and Quick Sort.

Selection Sort: Repeatedly selects the minimum (or maximum) element from the unsorted portion and swaps it with the first element of the unsorted portion. It has O(n²) time complexity and is simple but inefficient for large arrays.
Bubble Sort: Repeatedly compares adjacent elements and swaps them if they are in the wrong order, effectively "bubbling" the largest element to the end in each pass. It also has O(n²) time complexity and is easy to implement.
Quick Sort: A divide-and-conquer algorithm that selects a pivot element and partitions the array such that elements less than the pivot are on one side and elements greater are on the other. It recursively sorts the partitions. Quick Sort is efficient, with average O(n log n) time complexity, and suitable for large datasets.
Important points:

Selection and Bubble Sort are simple but inefficient for large arrays.
Quick Sort is much faster in practice but requires recursion and extra stack space.
Sorting improves the efficiency of algorithms like binary search.
Program 1: Selection Sort
# Logic:
Repeatedly find the minimum element from the unsorted portion of the array. Swap it with the first element of the unsorted portion. Continue until the array is fully sorted.

# Algorithm:
Start
Input the size of the array.
Input array elements.
For each position in the array, find the minimum element in the unsorted part.
Swap the minimum element with the first element of the unsorted part.
Repeat until all elements are sorted.
Display the sorted array.
End
# Program 2: Bubble Sort
Logic:
Compare adjacent elements and swap them if they are in the wrong order. Repeat this process for each element so that the largest elements "bubble" to the end.

# Algorithm:
Start
Input the number of elements.
Input array elements.
Repeat for each element:
Compare adjacent elements.
Swap if needed.
Continue passes until the array is sorted.
Display the sorted array.
End
# Program 3: Quick Sort
Logic:
Select a pivot element. Partition the array into two halves: elements less than pivot on left, elements greater than pivot on right. Recursively apply the same procedure to the left and right partitions.
# Algorithm:
Start
Input the number of elements.
Input array elements.
Select a pivot element.
Partition the array around the pivot.
Recursively sort the left and right partitions.
Display the sorted array.
End
# Conclusion
Sorting is fundamental for organizing data efficiently. Selection Sort and Bubble Sort are easy to implement but inefficient for large arrays. Quick Sort is highly efficient for large datasets due to its divide-and-conquer approach. Understanding sorting techniques is essential for algorithm design, data organization, and preparing arrays for faster searching algorithms.
