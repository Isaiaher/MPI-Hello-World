# MPI Hello World

## Compile the program

```
mpicc mpi_hello_world.c -o mpi_hello_world
```

## Run the program on 2 cores

```
mpirun -np 2 ./mpi_hello_world
```

## Output

```
Hello world from processor we28841, rank 0 out of 2 processors
Hello world from processor we28841, rank 1 out of 2 processors
```
