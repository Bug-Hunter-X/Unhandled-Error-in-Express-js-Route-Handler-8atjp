# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when parsing user input.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version.

The original code attempts to convert a user ID from a request parameter to an integer without validating the input.  This can lead to errors if the ID is not a valid number.

The solution adds input validation to prevent these errors, ensuring a more robust and reliable application.