# Java ArrayIndexOutOfBoundsException
This repository demonstrates a common Java error: the ArrayIndexOutOfBoundsException. The `bug.java` file contains code that throws this exception. The `bugSolution.java` file provides a corrected version.

**Problem:** The original code attempts to access an array element using an index that is out of bounds. 

**Solution:** The corrected code adds a check to ensure that the index is within the valid range of the array before attempting to access the element.  Alternative solutions might involve using a `try-catch` block to handle the exception gracefully.