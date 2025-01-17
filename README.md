# Express.js Route Handler Bug

This repository demonstrates a common bug in Express.js route handlers: missing error handling for invalid input.

The `bug.js` file contains a route handler that fetches a user by ID.  It fails to handle cases where the ID is not a number, leading to potential errors.

The `bugSolution.js` file provides a corrected version with proper error handling.