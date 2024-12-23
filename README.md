# Unexpected C Output: Post-Increment Operator

This repository demonstrates a common, yet subtle, error in C programming involving the post-increment operator (`x++`). The code appears simple, but the output might be counter-intuitive for beginners.

## The Bug

The `bug.c` file contains a program that initializes an integer variable, then prints its value twice using post-increment. The order of operations and the post-increment's behavior are not clearly understood leading to an incorrect assumption on the output.

## The Solution

The `bugSolution.c` file provides a corrected and improved approach.  It clearly shows how the post-increment operator functions and ensures a clearer understanding of its effect on the variable's value.

## Running the Code

Both programs can be compiled and run using a standard C compiler (like GCC):

```bash
gcc bug.c -o bug
./bug
gcc bugSolution.c -o bugSolution
./bugSolution
```