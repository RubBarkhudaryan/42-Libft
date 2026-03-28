# 42 Libft

## Overview
Libft is a foundational C library project at 42 where standard C functions are reimplemented and extended with custom utilities.

This library is reused in many later projects.

Because many 42 projects restrict external libraries, Libft becomes the base toolkit used across the cursus.

## Features
- Character checks and conversions
- String operations
- Memory operations
- Conversion helpers such as atoi and itoa
- Allocation utilities
- Linked-list bonus API

## Function Groups

### Libc-Like Core
Reimplemented functions for memory and string handling provide predictable, reusable primitives for future projects.

### Utility Layer
Helpers like split, trim, substr, join, and integer/string conversion reduce duplicate logic in later codebases.

### Linked List Bonus
List operations (create, add, iterate, map, clear) introduce dynamic data structure management patterns under strict memory rules.

## Quality Goals
- Consistent naming and API design
- Clear ownership and free responsibilities
- Correct edge-case handling (NULL input, empty strings, boundaries)
- Norm-compliant and reusable code style

## Build
Mandatory:
- make

Bonus:
- make bonus

Clean:
- make clean
- make fclean
- make re

## Usage
Include:
- libft.h

Link:
- libft.a

Example link usage:
- cc main.c -L. -lft -o app

## Project Structure
- ft_*.c: function implementations
- libft.h: public API
- Makefile: compilation and archiving

Header-first usage model:
- include libft.h in project files
- compile and link against libft.a

## Key Learnings
- Writing robust reusable C code
- API consistency and modularity
- Defensive behavior for edge cases

## Notes
Libft is the long-term foundation for many 42 projects such as printf, get_next_line, push_swap, minishell, and beyond.
