# MongoDB $inc Operator Error: Invalid Increment Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, providing a string value to `$inc` results in an error.

## Bug

The `bug.js` file contains code that attempts to increment a counter field using a string value ('1') instead of a numerical value (1).

## Solution

The `bugSolution.js` file shows the corrected code where the increment value is a number, resolving the error.  Correct usage of the `$inc` operator is essential for reliably updating numerical fields in MongoDB documents.