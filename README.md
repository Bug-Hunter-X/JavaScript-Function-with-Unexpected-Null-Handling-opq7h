# JavaScript Function with Unexpected Null Handling

This repository demonstrates a common, subtle bug in JavaScript related to null and undefined values in function arguments.

The `bug.js` file contains a function that explicitly handles null values.  However, it does not handle other falsy values like `undefined`, `0`, `false`, or empty strings.  This can lead to unexpected behavior or errors. 

The `bugSolution.js` file provides a solution to this by explicitly checking for `undefined` as well using the strict equality operator (`===`). 

This example highlights the importance of robust error handling and careful consideration of potential input values when writing JavaScript functions.