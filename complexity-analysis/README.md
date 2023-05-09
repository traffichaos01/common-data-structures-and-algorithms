# Complexity Analysis

## Key Definitions

### Complexity Analysis
The process of determining how efficient an algorithm is. Complexity analysis involves finding both the time complexity and space complexity of an algorithm.
Used to compare algorithms from one and another. Complexity analysis does not involve anything other than the worst-case scenario. We care about the input of the function as it increases in value, we keep the highest power of each input variable, but we would drop any coefficients.

### Time Complexity
A measure of how fast an algorithm runs, expressed in Big O notation.

### Space Complexity
A measure of how much auxiliary memory an algorithm takes up, expressed in Big O notation.

## Big O Notation
Notation used to describe the time and space complexity of algorithms.

Variables such as n and m used in Big O notation denote the sizes of inputs to algorithms. 
For example, O(n) might be the time complexity of an algorithm that traverses through an array of length n and through a
string of length n; similarly, O(n + m) might bne the time complexity of an algorithm that traverses through an array of
 length n and through a string of length m.


 
### Common Complexities and their Big O notations, ordered from fastest to slowest:
- Constant: O(1)
- Logarithmic: O(log(n))
- Linear: O(n) //If I halve my calculation space (binary tree) after every step, could be logarithmic time complexity.
- Log-Linear: O(nlog(n))
- Quadratic: O(n^2)
- Cubic: O(n^3)
- Exponential: O(2^n)
- Factorial: O(n!)

Constant values or linear asymptotic behaviour is cancelled out in asymptotic analysis with n to a higher power is involved