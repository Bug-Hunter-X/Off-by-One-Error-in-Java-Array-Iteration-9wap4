# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition `i <= arr.length` attempts to access an index that is out of bounds.  Arrays in Java are zero-indexed, meaning the valid indices range from 0 to `arr.length - 1`.

The `Bug.java` file contains the buggy code, while `BugSolution.java` provides the corrected version.