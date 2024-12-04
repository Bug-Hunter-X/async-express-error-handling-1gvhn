# Unhandled Promise Rejection in Async Express.js Route

This repository demonstrates a common error in Node.js applications involving unhandled promise rejections in asynchronous operations within Express.js routes.

## The Bug
The `bug.js` file contains an Express.js server with a route that simulates an asynchronous operation.  The operation randomly throws an error, which is not properly handled, leading to an unhandled promise rejection.

## The Solution
The `bugSolution.js` file demonstrates how to properly handle this error using a `try...catch` block within the asynchronous operation or by attaching error handlers to the promise itself.