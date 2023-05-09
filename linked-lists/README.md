# Linked Lists

Data structure that is built to be reversed.
Purpose is for each node to hold pointer to next node in linked list.
Could also be stored anywhere in memory landscape.
As we read memory contiguosly.


## Singly Linked List
Get: Constant Time Complexity O(i),where i is element index, O(1) space
Set: O(i) time, O(i) space

Init: O(n) space/time., each node has a value and reference to next node, have to allocate n chunks of memory
Copy: O(n) space/time
Traverse O(n) time, O(1) space

Insertion:
- New Head: O(1) time/space
- Unless you have reference to position of node you want to insert at, O(n) time.
- New Tail: O(n) time/space

## Double Linked List
You have reference to both head and TAIL.
Every node has pointer to next node and previous node.

This means that insertion for new tail is O(1) time/space.