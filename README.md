# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The error arises from incorrectly using the `<=` operator in the loop condition, leading to an `ArrayIndexOutOfBoundsException`. The solution shows how to correct the loop to iterate within the valid array bounds.  This is a classic example of a subtle bug that can cause unexpected behavior and crashes.

The `bug.java` file contains the erroneous code. The corrected code is in `bugSolution.java`.