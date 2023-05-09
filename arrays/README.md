# Arrays

## Static Arrays
Pre-Allocated memory for fixed array size.
Accessing element is O(1) time as we know memory where static array memory sits and O(1) space.
Setting element is O(1) time as we know where element sits and O(1) space.
Space complexity is O(n) as well as initilization.
Traversing Array is O(n) time and O(1) space.
Copy arrays is O(n) space and time.
Insert operation is O(n) time complexity and O(1) space complexity as you copy and remove memory for previous array..

## Dynamic Arrays
Allocates twice as much memory as what you are asking for, potentially more/less in python.
Insert operation could be O(1) or O(n) complexity, but we allow it to be constant time unless we are optimizing for all cases. O(n) time for insert in middle of array.
Amortized analysis.

Popping is O(1) time-space complexity at the end of array, pop at start or middle is O(n). Treat array as queue or stack and pop initial index to treat operation as O(1) for time sake. Way to cut corner in interview.
