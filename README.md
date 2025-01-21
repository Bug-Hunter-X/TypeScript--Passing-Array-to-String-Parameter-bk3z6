# TypeScript Bug: Passing Array to String Parameter

This repository demonstrates a common TypeScript error that occurs when attempting to pass an array to a function expecting a string parameter. The error message is shown in the console, but the underlying issue is that the types do not match. This can lead to unexpected runtime errors or even silent failures.

## Bug Description
The `greeter` function expects a string argument, but the `user` variable is an array of strings. TypeScript will throw an error during compilation because it identifies this type mismatch.

## Solution
The solution is to either modify the function signature to accept an array or to access an individual element from the array before passing it to the function.