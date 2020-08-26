# Parallel-Matrix

This program was designed to calculate the runtime of three different parallel implementations of NxN matrix multiplication in C using OpenMP. The difference in implementation is largely to see how changing the order of loop iterators in nested for loops can affect memory access times and overall runtime. A few other matrix operations, like matrix transposition, are also included.

## Compilation

gcc -fopenmp -lm -O3 -o executable_name matrix.c

## Execution

./executable_name matrix_size number_of_processors
