# Unhandled Undefined Object in JavaScript Function

This repository demonstrates a common error in JavaScript where a function fails to handle the case where an object is undefined. The function `foo` attempts to access the `length` property of its argument, which causes a `TypeError` when the argument is `undefined`.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version that handles the undefined case gracefully.

## Bug

The bug lies in the lack of a check to see if the input `a` is undefined before accessing `a.length`.  This leads to an unhandled exception.

## Solution

The solution involves adding a check for undefined before accessing `a.length`. This prevents the error from occurring and allows the function to handle undefined inputs gracefully.