# Strings
Array of integers, where each character in a given string is mapped to an integer via some character-encoding standard like ASCII.
Strings are immutable in python.

- Traverse => O(n) T, O(1) S
- Copy => O(n) ST
- Get => O(1) ST
- Mutate (instert/append/delete value) => must be copied => O(n) ST