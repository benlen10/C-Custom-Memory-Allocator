# Custom Memory Allocator

NOTICE: This project was recently moved to its own repository. It was originally developed in the ‘Current’ repository (Now renamed to [UniCade](https://github.com/benlen10/UniCade)) which contains the previous commits and versions.  

# Project Description
- This program is designed to replace the C memory allocator (malloc) and dynamically allocate memory.
- This program also allows you to print out a memory dump by calling the Mem_Dump function (See available functions below)

- This program was originally developed as a school project at UW Madison.

# Basic Usage (Public Functions)
- int Mem_Init(int sizeOfRegion)
- void* Mem_Alloc(int size)
- int Mem_Free(void *ptr)
- Mem_Dump()