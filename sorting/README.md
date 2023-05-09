# Sorting Algorithms
Helpful to have helper swap function

## .sort()
O(n) time/space
TimSort, derived from merge sort and insertion sort. 

## Bubble Sort
O(n^2) Time, O(1) Space

While list is not sorted, Passs through every element and compare it with the next element in the list, if the current element is greater than the nexrt element, swap them. 
If a full pass goes through without a change, list is sorted.

## Insertion Sort
O(n^2) Time, O(1) Space

Tentatively sort list, take first element for instance as sorted number, now look at rest of list and insert next number in sorted list by comparing if it is higher or lower than highest value in sorted list, then keep swapping in sorted list until there is no more values in unsorted list.