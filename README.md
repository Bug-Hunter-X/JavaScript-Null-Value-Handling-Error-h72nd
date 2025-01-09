# JavaScript Null Value Handling

This repository demonstrates a common error in JavaScript: incorrect handling of null values. The `foo` function adds two numbers, but it doesn't correctly handle cases where one or both arguments are null.  This can lead to unexpected behavior or errors if null values are possible.

The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version that uses strict equality (`===`) for null checks and provides a default value or error handling as needed.

## How to reproduce
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js`.
3. Run the `bug.js` file to observe the incorrect behavior. 
4. Run the `bugSolution.js` file to see how to correctly handle null values. 