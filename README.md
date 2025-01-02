# Handling Null Values in JavaScript

This repository demonstrates a common JavaScript issue and its solution: gracefully handling null values in function arguments to prevent unexpected errors.

## Problem:

In many JavaScript functions, you might encounter situations where a function argument could potentially be null.  If you don't explicitly handle such cases, you may encounter unexpected errors, such as `TypeError: Cannot read properties of null (reading '...')`. 

## Solution:

The provided code explicitly checks for null values before performing any operations.  If either or both arguments are null, the function returns null, avoiding any runtime errors.  This is a robust and defensive programming practice.

## Usage:

1.  Clone this repository.
2.  Open `bug.js` to view the code with the potential error.
3.  Open `bugSolution.js` to see the improved and corrected version.
4.  Run the scripts with a node environment `node bug.js` and `node bugSolution.js`

This demonstration showcases simple, but crucial error handling techniques for building more reliable JavaScript code.