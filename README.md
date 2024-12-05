# Infinite Loop Bug in JavaScript

This repository demonstrates a common error in JavaScript loops where the loop counter variable is not incremented, leading to an infinite loop. The `bug.js` file contains the buggy code, and `bugSolution.js` provides the corrected version.

## Bug Description
The original code has a while loop that intends to iterate from 0 to 9, printing the values of the counter variable. However, the counter variable `i` is not incremented inside the loop. This omission prevents the loop condition (`i < 10`) from ever becoming false, resulting in an infinite loop.

## Solution
The solution involves adding `i++` within the loop to properly increment the counter variable. This ensures that the loop condition eventually becomes false and the loop terminates correctly.

## How to Reproduce
1. Clone this repository.
2. Run `node bug.js` to observe the infinite loop.
3. Run `node bugSolution.js` to see the corrected code in action.