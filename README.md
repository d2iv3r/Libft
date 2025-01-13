## Overview
**Libft** is a custom C library that re-implements standard C library functions. It serves as a foundational project in the 42 curriculum, helping students understand low-level programming, memory management, and the structure of C libraries.

This project challenges you to build a library of essential C functions that will be reused in future projects.

---

## Features

**Functions List**
1. String Manipulation:
`ft_strlen:` Calculates the length of a string.
`ft_strcpy:` Copies a string.
`ft_strcpy:` Copies a string.
`ft_strcat:` Concatenates two strings.
`ft_strdup:` Duplicates a string.


2. Memory Management:
`ft_memset:` Fills memory with a constant byte.
`ft_memcpy:` Copies memory area.
`ft_memmove:` Moves memory safely.
`ft_bzero:` Sets memory to zero.


3. Character Checks:
`ft_isalpha:` Checks if a character is alphabetic.
`ft_isdigit:` Checks if a character is a digit.
`ft_isalnum:` Checks if a character is alphanumeric.
`ft_toupper:` Converts a character to uppercase.
`ft_tolower:` Converts a character to lowercase.


4. Linked List Utilities:
`ft_lstnew:` Creates a new linked list node.
`ft_lstadd_front:` Adds a node to the beginning of a list.
`ft_lstsize:` Counts the number of nodes in a list.
`ft_lstlast:` Returns the last node of the list.

---

## Usage

Once you've built your `libft.a` library, you can use it in your C projects by linking it during compilation. Here's how:

### 1. **Building the Library**
To build the library, run:
```bash
make
```

### 2. **Using Libft in Your Project**
You can include libft.a in your project by:
Including the Header File
Add `#include "libft.h"` at the top of your .c files to access the library functions.

Linking the Library During Compilation
Use the -L and -l flags to link the library when compiling your project. For example:

```bash
gcc -Wall -Wextra -Werror your_file.c -L. -lft -o your_program
```