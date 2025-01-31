# Type 'string' is not assignable to type 'number' in TypeScript

This repository demonstrates a common type error in TypeScript where a string is passed as an argument to a function expecting a number. The TypeScript compiler will catch this error at compile time. This example highlights the importance of type checking in TypeScript for preventing runtime errors.

## Bug

The bug is present in `bug.ts`.  The function `add` is defined to take two numbers as arguments, but the code calls the function with a string '2' as the second argument, resulting in a compile-time type error.

## Solution

The solution is in `bugSolution.ts`.  The bug is fixed by ensuring the second argument is a number. This can be done through explicit type casting or by ensuring the value is of the correct type at the point of usage.