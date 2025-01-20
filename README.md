# Uncommon JavaScript Error: Missing Operator Case and Division by Zero

This repository demonstrates a common error in JavaScript:  forgetting to handle all cases in a switch statement, and the division by zero error.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.

## Bug Description
The original code implements a simple calculator using a switch statement to handle different arithmetic operations. However, it lacks a case for the modulo operator ('%'), and it does not handle division by zero.

## Solution
The corrected code in `bugSolution.js` adds a case for the modulo operator and includes error handling for division by zero.