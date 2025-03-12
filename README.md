# Libft

## Description

Libft is my first custom C library. This project involves recreating various functions from the standard C library, as well as implementing additional functions that will be useful for future projects. The goal is to deepen your knowledge of string manipulation, dynamic memory allocation, and linked lists.

## Project Structure

The project is organized into the following components:

- **Part 1 - Reimplementation of Libft functions**
- **Part 2 - Additional functions**
- **Bonus - Linked list manipulation**

## Features

### Part 1 - Libft Functions

Reimplementation of common functions from the standard C library, all prefixed with `ft_`, including:

- ft\_isalpha, ft\_isdigit, ft\_isalnum, ft\_isascii, ft\_isprint
- ft\_strlen, ft\_memset, ft\_bzero, ft\_memcpy, ft\_memmove
- ft\_strlcpy, ft\_strlcat, ft\_toupper, ft\_tolower
- ft\_strchr, ft\_strrchr, ft\_strncmp, ft\_memchr, ft\_memcmp
- ft\_strnstr, ft\_atoi
- ft\_calloc, ft\_strdup

### Part 2 - Additional Functions

Implementation of functions that assist with string and memory handling, including:

- ft\_substr, ft\_strjoin, ft\_strtrim, ft\_split
- ft\_itoa, ft\_strmapi, ft\_striteri
- ft\_putchar\_fd, ft\_putstr\_fd, ft\_putendl\_fd, ft\_putnbr\_fd

### Bonus - Linked List Manipulation

To expand the library's functionalities, functions for linked list manipulation were included:

- ft\_lstnew, ft\_lstadd\_front, ft\_lstsize, ft\_lstlast
- ft\_lstadd\_back, ft\_lstdelone, ft\_lstclear
- ft\_lstiter, ft\_lstmap

## How to Use

### Compilation

To compile the library, simply run:

```sh
make
```

This will generate the `libft.a` file.

### Usage in a Project

To use the library in your project, include it as follows:

```c
#include "libft.h"
```

## Project Rules

- The code follows the 42 Norm.
- The `Makefile` contains the rules `all`, `clean`, `fclean`, `re`, and `bonus`.
- All dynamically allocated memory must be properly freed.
- Global variables are not allowed.
- Helper functions must be declared as `static`.

## Author

Pedro Cristóvão Veiga Correia

