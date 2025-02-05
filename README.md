# Uninitialized Property Access in C#

This example demonstrates a common error in C#: accessing a property of a class before it has been initialized.  This can lead to unexpected behavior, including exceptions or incorrect calculations.

The `bug.cs` file contains the code with the error, while `bugSolution.cs` shows the corrected version.

## How to reproduce:
1. Compile and run the code in `bug.cs`.
2. Observe the potential exceptions or incorrect results depending on the uninitialized value.
3. Compare with the corrected code in `bugSolution.cs` to see how to avoid this error.

## Solution:
The solution involves initializing the property with a default value or ensuring that the property is assigned a value before being accessed.