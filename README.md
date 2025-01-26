# Ada Array Index Out of Bounds and Exception Handling

This repository demonstrates a common error in Ada programming involving array index out-of-bounds issues and provides a robust solution using exception handling.

The `bug.ada` file contains code that attempts to manipulate an array. This code has a potential to go out of bounds if the loop isn't carefully constructed. The `bugSolution.ada` demonstrates the proper way to handle this, preventing runtime errors.

## How to Run

1.  Install an Ada compiler (e.g., GNAT).
2.  Compile and run the Ada code using your compiler.
3. Observe the difference in behavior between the original code and the solution.

## Additional Notes

Ada's strong typing and range checks make it less prone to such errors than many other languages, but careful attention is still required to avoid problems.  This example highlights the importance of careful indexing and appropriate exception handling. This is especially important in critical systems where unexpected array behavior can lead to major problems. 