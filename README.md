# Sorting Visualization

## Purpose
  This project's purpose was to demonstrate procedure of implementing sorting algorithms and how these algorithms handle data in real time.
  
  This project has also been used in Algirithm Tutorials for IIIT Lucknow Freshman. (see Usage in Algorithm Tutorials)
___

## Features
  This project features many sorts including:

  Basic Sorts:
  - Bubble sort
  - Insertion sort
  - Selection sort
  - Merge sort

  Advanced Sorts:
  - Gnome Sort
  - Shell Sort
  - Radix Sort

  You are able to change the speed at which the sorts operate as well as the size of the data set.
  
___

## Descripton - Basic Sorts

1) Bubble Sort

Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list to be sorted, compares each pair of adjacent items and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted. The algorithm, which is a comparison sort, is named for the way smaller or larger elements "bubble" to the top of the list. Although the algorithm is simple, it is too slow and impractical for most problems even when compared to insertion sort. It can be practical if the input is usually in sorted order but may occasionally have some out-of-order elements nearly in position.

2) Insertion Sort

It is a simple sorting algorithm that is relatively efficient for small lists and mostly sorted lists, and is often used as part of more sophisticated algorithms. It works by taking elements from the list one by one and inserting them in their correct position into a new sorted list. In arrays, the new list and the remaining elements can share the array's space, but insertion is expensive, requiring shifting all following elements over by one. Shell sort (see below) is a variant of insertion sort that is more efficient for larger lists.

3) Selection Sort

Selection sort is an in-place comparison sort. It has O(n2) complexity, making it inefficient on large lists, and generally performs worse than the similar insertion sort. Selection sort is noted for its simplicity, and also has performance advantages over more complicated algorithms in certain situations. The algorithm finds the minimum value, swaps it with the value in the first position, and repeats these steps for the remainder of the list. It does no more than n swaps, and thus is useful where swapping is very expensive.

4) Merge Sort

Merge Sort takes advantage of the ease of merging already sorted lists into a new sorted list. It starts by comparing every two elements (i.e., 1 with 2, then 3 with 4...) and swapping them if the first should come after the second. It then merges each of the resulting lists of two into lists of four, then merges those lists of four, and so on; until at last two lists are merged into the final sorted list. Of the algorithms described here, this is the first that scales well to very large lists, because its worst-case running time is O(n log n). It is also easily applied to lists, not only arrays, as it only requires sequential access, not random access. However, it has additional O(n) space complexity, and involves a large number of copies in simple implementations.


reference : https://en.wikipedia.org/wiki/Sorting_algorithm
  
___

## Usage in Algorithm Tutorials
  This visualizer was used to introduce college freshman to sorting algorithms in their competitive programming lectures, by showing them the procedural flow of these algorithms.
  (Acted as a TA for the same.) 
