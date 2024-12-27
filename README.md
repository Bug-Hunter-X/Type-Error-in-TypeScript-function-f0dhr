# Type Error in TypeScript Function
This repository demonstrates a common type error in TypeScript where a string is passed as an argument to a function expecting a number. The solution shows how to correctly type check inputs to prevent such errors. 

## Bug
The `add` function is declared to accept two numbers. However, the code attempts to pass a string as the second argument, leading to a type error at compile time.  This error highlights the importance of type safety in TypeScript.

## Solution
The solution employs a type guard to check if the inputs are numbers before performing the addition operation.  If either input is not a number, it throws an error; otherwise, the addition happens as expected.