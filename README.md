# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`. The bug is caused by attempting to access an array element using an index that is out of bounds.

The `bug.java` file contains the erroneous code. The `bugSolution.java` file provides the corrected code.

**How to reproduce the bug:**
1. Compile `bug.java`.
2. Run the compiled class.
3. Observe the `ArrayIndexOutOfBoundsException`.

**How to fix the bug:**
Modify the loop condition to correctly iterate within the array's bounds. Use 'i < arr.length'.