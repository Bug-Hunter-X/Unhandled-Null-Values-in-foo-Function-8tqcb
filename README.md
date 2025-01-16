# Unhandled Null Values in foo Function

This repository demonstrates a common JavaScript bug involving the mishandling of null values in a function. The `foo` function does not explicitly handle cases where the input parameters `a` or `b` are null, leading to potential errors or unexpected behavior.

The `bug.js` file contains the buggy implementation, while `bugSolution.js` provides a corrected version that properly handles null values.

## Bug Description

The original `foo` function lacks error handling for null values. When either `a` or `b` is null, the function's behavior is undefined.  This could result in runtime errors or produce incorrect results, depending on subsequent operations.

## Solution

The solution in `bugSolution.js` directly addresses this issue by explicitly checking for null values at the beginning of the function using a conditional statement.  If either parameter is null, the function returns early, preventing potential problems.