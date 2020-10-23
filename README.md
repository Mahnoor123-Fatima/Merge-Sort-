# Merge_Sort
Implementation of Merge Sort Algorithm in C++

## Merge_Sort:
In computer science, merge sort is an efficient, general-purpose, comparison-based sorting algorithm. Most implementations produce a stable sort, which means that the order of equal elements is the same in the input and output. Merge sort is a divide and conquer algorithm that was invented by John von Neumann in 1945

## Algorithm:
The merge() function is used for merging two halves. The merge(arr, l, m, r) is a key process that assumes that arr[l..m] and arr[m+1..r] are sorted and merges the two sorted sub-arrays into one. 
```
MergeSort(arr[], l,  r)
If r > l
     1. Find the middle point to divide the array into two halves:  
             middle m = (l+r)/2
     2. Call mergeSort for first half:   
             Call mergeSort(arr, l, m)
     3. Call mergeSort for second half:
             Call mergeSort(arr, m+1, r)
     4. Merge the two halves sorted in step 2 and 3:
             Call merge(arr, l, m, r)
 ```
 ## Example:
 ![merge_sort_example](https://github.com/Mahnoor123-Fatima/Merge-Sort-/blob/main/660px-Merge_sort_algorithm_diagram.svg.png)
 
 ## Time Complexity:
 Time complexity of Merge Sort is  θ(nLogn) in all 3 cases (worst, average and best) as merge sort always divides the array into two halves and takes linear time to merge two halves.
 
 ## Applications of Merge Sort Algorithm:
 - Merge Sort is useful for sorting linked lists in O(n Log n) time.
 - Merge sort can be implemented without extra space for linked lists.
 - Merge sort is used for counting inversions in a list.
 - Merge sort is used in external sorting.
 
 --------------------------------------------------------------------------------------------------------


[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](#)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat&label=Contributions&colorA=red&colorB=black	)](#)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)
