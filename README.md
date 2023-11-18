# Parallel_Programming_LAB

## OPEN MP
commands to execute 
```
gcc -fopenmp -o <executable_name> <file_name>.c
```

```
time ./<executable_name>
```
Example 
- To compile
```
gcc -fopenmp test test.c   
```
- To run the executable  
```
time ./test
```

## MPI 
commands to execute 
```
mpicc <file_name>.c -o <executable_name>
```

```
mpirun -n <number_of_processes> <executable_name>
```
Example 
- To compile
```
mpicc test.c -o test
```
- To run the executable  
```
mpirun -n 2 test
```
