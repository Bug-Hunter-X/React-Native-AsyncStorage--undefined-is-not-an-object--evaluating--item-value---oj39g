# React Native AsyncStorage Undefined Error

This repository demonstrates a common error encountered when using AsyncStorage in React Native applications: accessing data before it's fully loaded results in undefined values.  The example showcases the problem and its solution using async/await.

## Problem

The `bug.js` file contains code that attempts to access AsyncStorage data synchronously, leading to an undefined value error if the data hasn't been retrieved yet.

## Solution

The `bugSolution.js` file demonstrates the correct approach using async/await to ensure the data is loaded before being accessed. This prevents the undefined error and makes the code more robust.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run the app on your emulator or device.
4. Observe the console for error messages in `bug.js` and the successful output of `bugSolution.js`.

This example highlights the importance of properly handling asynchronous operations in React Native development to avoid common errors.