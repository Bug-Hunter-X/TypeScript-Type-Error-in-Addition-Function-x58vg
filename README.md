# TypeScript Type Error in Addition Function

This repository demonstrates a common type error in TypeScript: passing an incorrect parameter type to a function.

## Bug
The `add` function is defined to take two numbers as input and return their sum. However, in the code, we pass a string("10") as the second argument. TypeScript's type system correctly flags this as an error.

## Solution
The solution is to ensure that both parameters passed to the `add` function are numbers.  Type checking prevents runtime errors by catching these issues at compile time. 