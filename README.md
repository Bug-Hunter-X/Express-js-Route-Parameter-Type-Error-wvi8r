# Express.js Route Parameter Type Error

This repository demonstrates a common error in Express.js applications related to parsing route parameters.  The bug arises from the lack of proper error handling and type checking when dealing with route parameters that are expected to be numbers.  The solution showcases how to handle these parameters correctly to prevent unexpected errors.

## Bug

The `bug.js` file contains the erroneous code.  It attempts to access user data based on a numerical ID passed as a route parameter. However, it fails to correctly handle cases where the parameter is not a number, resulting in unexpected behavior.

## Solution

The `bugSolution.js` file provides the corrected implementation. It adds comprehensive error handling and type checking to ensure that the route parameter is a valid number before processing it. This prevents the application from crashing or returning unexpected responses when encountering invalid input.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory in your terminal.
3. Run `node bug.js` to see the error. 
4. Run `node bugSolution.js` to see the corrected implementation.