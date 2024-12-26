# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The provided code attempts to access an array element beyond its valid index range within a `for` loop, leading to the exception.
The solution provides a corrected version with proper loop conditions.  This example highlights the importance of careful array index management in Java.
## Bug Description
The original Java code has a flawed `for` loop condition that leads to an `ArrayIndexOutOfBoundsException`. The loop iterates one element beyond the array's size.
## Solution
The corrected code modifies the loop condition to ensure it iterates only within the valid index range of the array.