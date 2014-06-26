ArithmeticGrammer
=================
A grammar definition which is capable of evaluating arithmetic expressions using [JavaCC](https://javacc.java.net).
Besides evaluating the grammar will take note of unused variables, double definitions of variables, and if a variable is not used.

## Example
```
a = 1;
b = 2;
a + b + 1 =
```
The given example will return 4 as a number.

