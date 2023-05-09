# Hash Tables
Dict in python

Init is O(n) time, O(n) space.

Insertion, Deletion or searching for value given key are constant time O(1) operation on average.
In worst case with key collisions, time operations are O(n), popular implementations can accept constant time operations on average.
Worst case if specified that you need constant time operations.
Our keys can be all data types.

Hash tables are built on dynamic arrays.
Key will be hashed using hashing function to get index for value.

## Hashing side note.
Can convert characters in string to respective ascii encoded values and sum them up.
Can use modulo remainder for index in dynamic array, where each element in array is a linked list to handle collisions, where the hashing function of two keys returns the same index in array. To know which value in linked list, each node in linked list needs to point back to original key.
