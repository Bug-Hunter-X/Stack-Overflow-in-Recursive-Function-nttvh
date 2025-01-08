# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow. The `foo()` function calculates the factorial of a number recursively. However, if the input is too large, it will lead to a stack overflow because the function calls itself too many times without terminating.

The solution provided implements an iterative approach to calculate the factorial, avoiding the recursive calls and preventing stack overflow errors.

## How to reproduce the error

1.  Compile the `bug.hack` file using the Hack compiler.
2.  Run the compiled code.
3.  Observe the stack overflow error.
