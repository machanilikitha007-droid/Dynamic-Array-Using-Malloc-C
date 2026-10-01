# Dynamic Array Using malloc() in C

## Project Description

A simple C program that demonstrates dynamic memory allocation using the `malloc()` function. The program creates an integer array based on the size entered by the user, stores the elements, calculates their sum, and finally releases the allocated memory using `free()`.

## Features

- Accept array size from the user
- Allocate memory dynamically using `malloc()`
- Store elements in the dynamically allocated array
- Display array elements
- Calculate the sum of elements
- Release allocated memory using `free()`
- Check whether memory allocation was successful

## Technologies Used

- C
- Dynamic Memory Allocation
- `malloc()`
- `free()`
- Arrays
- Pointers

## How to Run

1. Create a file named `dynamic_array_malloc.c`.
2. Compile the program using a C compiler.
3. Run the compiled program.

Example using GCC:

```bash
gcc dynamic_array_malloc.c -o dynamic_array_malloc
./dynamic_array_malloc

===== Dynamic Array Using malloc() =====
Enter number of elements: 5
Enter 5 elements:
Element 1: 10
Element 2: 20
Element 3: 30
Element 4: 40
Element 5: 50

Array elements are:
10 20 30 40 50

Sum = 150
Memory released successfully.

Author

M.Likitha
