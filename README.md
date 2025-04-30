# 42 Libft

42 Libft is a foundational project in the 42 curriculum that involves reimplementing a set of standard C library functions. This project not only reinforces your understanding of C language fundamentals but also lays the groundwork for subsequent projects by providing a reusable library.

## Overview

This project covers functions for:
- **Memory Management:** `memset`, `bzero`, `memcpy`, `memccpy`, `memcmp`, etc.
- **String Manipulation:** `strlen`, `strdup`, `strcpy`, `strncpy`, `strcat`, `strncat`, and more.
- **Character Checks:** Functions like `isalpha`, `isdigit`, `isalnum`, etc.
- **Additional Utilities:** Linked list functions and bonus functionalities.

## Installation

Clone the repository:
```
git clone https://github.com/RubBarkhudaryan/42-Libft.git
```

## Compile the library:
```
make
```
## Usage
Include the header file in your project:

```
#include "libft.h"
```

## Link your project against the compiled library:
```
gcc -L. -lft your_program.c -o your_program
```
## Project Structure
**Makefile** - automated compilation of program by using command ```make```

**C files** - source files where are the implementations of functions

**libft.h** - header file where were defined all the neccessary functions and macros

**Author
Rub Barkhudaryan**
