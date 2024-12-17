# React Native: Handling 'Cannot read properties of undefined (reading 'property')'

This repository demonstrates a common error in React Native applications and provides a solution. The error, 'Cannot read properties of undefined (reading 'property')', arises when attempting to access a property of an object that is currently undefined or null. This often occurs when dealing with asynchronous operations where data hasn't finished loading. 

The `bug.js` file illustrates the problematic code. The `bugSolution.js` file shows how to resolve the error using optional chaining and nullish coalescing operators.

## How to run

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` or `npx react-native run-ios`.