README
======

This package includes the following files.

|-- Driver.c [This is the driver program which will be used to invoke the MemoryManager.]
|-- MemoryManager.c [Allocate, deallocate data structures; populate elements in them and maintain a count of the medians of the structures divisible by 13]
|-- MemoryManager.h [Header file declaring the function exposed from MemoryManager]
|-- README.txt [This file]

To compile:
    make

To run:
    ./Driver.out <seed>

For example;
    ./Driver.out 1234

