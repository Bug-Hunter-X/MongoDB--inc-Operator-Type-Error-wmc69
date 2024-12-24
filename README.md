# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value as the increment will lead to an error or unexpected results. 

The `bug.js` file contains the incorrect implementation, while `bugSolution.js` provides the correct solution.

## Bug
The `$inc` operator is incorrectly used with a string value instead of a number. This results in a type error or unintended modification of the field.

## Solution
The corrected code uses a numeric value for the increment, ensuring the operation functions as intended. 