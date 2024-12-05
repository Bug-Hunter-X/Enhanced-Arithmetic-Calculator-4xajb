# Missing Modulo Operator in Basic Calculator

This repository demonstrates a common error in JavaScript: failing to handle all expected operators in a function.  The provided `operate` function performs basic arithmetic operations (+, -, *, /), but lacks support for the modulo operator (%).

The `bug.js` file contains the buggy code, and `bugSolution.js` provides a corrected version.

## Bug

The original code throws an error when the modulo operator (%) is used because it is not handled in the switch statement.

## Solution

The solution adds a case for the modulo operator (%) to the switch statement, ensuring that all common arithmetic operators are handled correctly.