# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution. The `bug.js` file contains code that throws a `TypeError` when an undefined value is passed to a function that attempts to access the `length` property.

The `bugSolution.js` file provides a corrected version of the function that handles undefined values gracefully.

## Bug Description
The original code fails to handle the case where the input `a` is `undefined`.  Attempting to access `a.length` when `a` is undefined results in a `TypeError`.

## Solution
The solution involves adding a check for `undefined` before accessing `a.length`.  If `a` is undefined, a default value (such as 0) is returned to prevent the error.