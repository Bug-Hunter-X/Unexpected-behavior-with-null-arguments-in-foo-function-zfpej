# Unexpected Null Handling in foo Function

This repository demonstrates a common JavaScript error involving unexpected behavior when null values are passed as arguments to a function.

## Bug Description
The `foo` function in `bug.js` does not handle null values gracefully.  When null is passed as either `a` or `b`, it results in unexpected behavior instead of returning a sensible default or throwing a clear error.

## Solution
The solution in `bugSolution.js` shows how to improve the `foo` function to address this.  Explicitly checking for null values and providing either a default value or handling null with a `try...catch` block is recommended.