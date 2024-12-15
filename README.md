# Incorrect use of $inc operator in MongoDB

This repository demonstrates a common error when using the `$inc` operator in MongoDB: providing a string value instead of a number.

The `bug.js` file shows the incorrect usage, while `bugSolution.js` provides the corrected code.

## Bug
The `$inc` operator in MongoDB is used to increment a numerical value.  If a string is passed as an argument, it will throw an error.

## Solution
Ensure that the value passed to the `$inc` operator is a number (integer or float).