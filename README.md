# Mini-libc

A lightweight and minimal C standard library implementation designed for embedded systems, operating system kernels, and bare-metal applications.

## Features

- **Minimalistic Implementation** – Provides only essential libc functionalities to keep the footprint low.
- **Custom Memory Management** – Includes a simple `malloc()` and `free()` for heap allocation.
- **String Handling** – Implements core string manipulation functions like `memcpy()`, `strlen()`, and `strcmp()`.
- **Standard I/O Support** – Basic implementations of `printf()` and `puts()`.
- **Optimized for Size and Performance** – Designed for environments where resources are limited.
- **Portability** – Can be adapted for various platforms with minimal modifications.

## Supported Functions

### Memory Management
- `malloc()`
- `free()`
- `memcpy()`
- `memset()`

### String Manipulation
- `strlen()`
- `strcmp()`
- `strcpy()`
- `strncpy()`

### Standard I/O
- `printf()` (basic format support)
- `puts()`

## Build & Usage

### Requirements
- GCC or Clang (or any C compiler supporting C99 or later)
- Make (optional, for build automation)

### Compilation
To build the library as a static archive:
```sh
make
```

