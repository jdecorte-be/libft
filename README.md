<header>
<h1 align="center">
  <a href="https://github.com/jdecorte-be/libft"><img src=".assets/banner.png" alt="libft" ></a>
  libft
  <br>
</h1>

<p align="center">
  A custom C library featuring re-implementations of standard libc functions and other useful utilities. A core project for the 42 school curriculum.
</p>

<p align="center">
<a href="https://www.42.fr">
    <img src="https://img.shields.io/badge/42-School%20Project-00BABC?logo=42&logoColor=white&labelColor=000000"
         alt="42 School Project">
  </a>
<a href="https://github.com/jdecorte-be/libft">
    <img src="https://img.shields.io/badge/Type-C%20Library-blue?logo=c&logoColor=white&labelColor=000000"
         alt="Type C Library">
  </a>
<a href="https://github.com/jdecorte-be/libft">
    <img src="https://img.shields.io/badge/Focus-libc%20Re--implementation-555?logo=c&logoColor=white&labelColor=000000"
         alt="Focus libc Re-implementation">
  </a>
<a href="https://en.wikipedia.org/wiki/C99">
    <img src="https://img.shields.io/badge/Standard-C99-A8B9CC?logo=c&logoColor=white&labelColor=000000"
         alt="Standard C99">
  </a>
</p>

<p align="center">
<a href="https://github.com/jdecorte-be/libft/actions">
    <img src="https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white&labelColor=000000"
         alt="CI GitHub Actions">
  </a>
  <a href="https://github.com/jdecorte-be/libft/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-GPL--3.0-AE81FF?labelColor=000000"
         alt="libft license">
  </a>
  <a href="https://github.com/jdecorte-be/libft/stargazers">
    <img src="https://img.shields.io/github/stars/jdecorte-be/libft?logo=star&logoColor=white&labelColor=000000&color=E6DB74"
         alt="libft stars">
  </a>
  <a href="https://github.com/jdecorte-be/libft/issues">
    <img src="https://img.shields.io/github/issues/jdecorte-be/libft?logoColor=white&labelColor=000000&color=orange"
         alt="libft issues">
  </a>
  <a href="https://github.com/jdecorte-be/libft">
    <img src="https://img.shields.io/github/repo-size/jdecorte-be/libft?logo=database&logoColor=white&labelColor=000000&color=AE81FF"
         alt="libft repo size">
  </a>
  <a href="https://github.com/jdecorte-be/libft">
    <img src="https://img.shields.io/github/languages/top/jdecorte-be/libft?logo=code&logoColor=white&labelColor=000000&color=A6E22E"
         alt="libft top language">
  </a>
</p>
<p align="center">
  <a href="#pushpin-index">:pushpin: Index</a> •
  <a href="#sparkles-what-is-libft">:sparkles: What is Libft?</a> •
  <a href="#bookmarktabs-list-of-fucntions">:bookmark_tabs: List of Fucntions</a> •
  <a href="#functions-from-ctypeh">Functions from `<ctype.h>`</a> •
  <a href="#functions-from-stringh">Functions from `<string.h>`</a> •
  <a href="#functions-from-stdlibh">Functions from `<stdlib.h>`</a> •
  <a href="#non-standard-functions">Non-standard functions</a>
</p>
</header>


![.assets/banner.png](.assets/banner.png)

Libft is a custom C library developed as a core project for the 42 school curriculum. It contains re-implementations of many standard C library functions, as well as a suite of additional utilities for string manipulation, memory management, and linked list operations.

This project is designed to provide a foundational set of tools for future C projects where standard libraries may be restricted.

## Function Reference

The library is organized into several parts: re-implementations of standard `libc` functions, a set of non-standard utility functions, and functions for manipulating linked lists.

### Part 1: Libc Functions

These functions mimic the behavior of their standard C library counterparts.

#### `<ctype.h>`

| Function | Description |
| :--- | :--- |
| [`ft_isalpha`](libft/ft_isalpha.c) | Checks if a character is alphabetic. |
| [`ft_isdigit`](libft/ft_isdigit.c) | Checks if a character is a digit (0-9). |
| [`ft_isalnum`](libft/ft_isalnum.c) | Checks if a character is alphanumeric. |
| [`ft_isascii`](libft/ft_isascii.c) | Checks if a character fits into the ASCII character set. |
| [`ft_isprint`](libft/ft_isprint.c) | Checks if a character is printable. |
| [`ft_toupper`](libft/ft_toupper.c) | Converts a character to its uppercase equivalent. |
| [`ft_tolower`](libft/ft_tolower.c) | Converts a character to its lowercase equivalent. |

#### `<string.h>` / `<strings.h>`

| Function | Description |
| :--- | :--- |
| [`ft_strlen`](libft/ft_strlen.c) | Calculates the length of a string. |
| [`ft_memset`](libft/ft_memset.c) | Fills a block of memory with a specific value. |
| [`ft_bzero`](libft/ft_bzero.c) | Fills a block of memory with zero-valued bytes. |
| [`ft_memcpy`](libft/ft_memcpy.c) | Copies a block of memory from a source to a destination. |
| [`ft_memmove`](libft/ft_memmove.c) | Copies a block of memory, handling overlapping areas safely. |
| [`ft_strlcpy`](libft/ft_strlcpy.c) | Copies a string to a buffer with size-checking. |
| [`ft_strlcat`](libft/ft_strlcat.c) | Concatenates a string to a buffer with size-checking. |
| [`ft_strchr`](libft/ft_strchr.c) | Locates the first occurrence of a character in a string. |
| [`ft_strrchr`](libft/ft_strrchr.c) | Locates the last occurrence of a character in a string. |
| [`ft_strncmp`](libft/ft_strncmp.c) | Compares up to `n` characters of two strings. |
| [`ft_memchr`](libft/ft_memchr.c) | Scans memory for the first occurrence of a character. |
| [`ft_memcmp`](libft/ft_memcmp.c) | Compares two blocks of memory. |
| [`ft_strnstr`](libft/ft_strnstr.c) | Locates a substring within the first `n` bytes of a string. |
| [`ft_strdup`](libft/ft_strdup.c) | Duplicates a string by allocating new memory. |

#### `<stdlib.h>`

| Function | Description |
| :--- | :--- |
| [`ft_atoi`](libft/ft_atoi.c) | Converts a string to an integer. |
| [`ft_calloc`](libft/ft_calloc.c) | Allocates memory for an array and initializes it to zero. |

### Part 2: Additional Functions

A collection of useful functions not found in the standard C library.

| Function | Description |
| :--- | :--- |
| [`ft_substr`](libft/ft_substr.c) | Allocates and returns a substring from a string. |
| [`ft_strjoin`](libft/ft_strjoin.c) | Allocates and returns a new string, result of concatenating two strings. |
| [`ft_strtrim`](libft/ft_strtrim.c) | Allocates and returns a copy of a string with specified characters removed from the beginning and end. |
| [`ft_split`](libft/ft_split.c) | Allocates and returns an array of strings obtained by splitting a string using a delimiter character. |
| [`ft_itoa`](libft/ft_itoa.c) | Allocates and returns a string representation of an integer. |
| [`ft_strmapi`](libft/ft_strmapi.c) | Applies a function to each character of a string to create a new string. |
| [`ft_striteri`](libft/ft_striteri.c) | Applies a function to each character of a string. |
| [`ft_putchar_fd`](libft/ft_putchar_fd.c) | Writes a single character to a given file descriptor. |
| [`ft_putstr_fd`](libft/ft_putstr_fd.c) | Writes a string to a given file descriptor. |
| [`ft_putendl_fd`](libft/ft_putendl_fd.c) | Writes a string to a file descriptor, followed by a newline. |
| [`ft_putnbr_fd`](libft/ft_putnbr_fd.c) | Writes an integer to a given file descriptor. |

### Bonus Part: Linked List Functions

Functions to create and manage a singly linked list.

| Function | Description |
| :--- | :--- |
| [`ft_lstnew`](libft/ft_lstnew.c) | Creates a new list element. |
| [`ft_lstadd_front`](libft/ft_lstadd_front.c) | Adds an element to the beginning of a list. |
| [`ft_lstsize`](libft/ft_lstsize.c) | Counts the number of elements in a list. |
| [`ft_lstlast`](libft/ft_lstlast.c) | Returns the last element of a list. |
| [`ft_lstadd_back`](libft/ft_lstadd_back.c) | Adds an element to the end of a list. |
| [`ft_lstdelone`](libft/ft_lstdelone.c) | Frees the memory of a single list element. |
| [`ft_lstclear`](libft/ft_lstclear.c) | Deletes and frees all elements of a list. |
| [`ft_lstiter`](libft/ft_lstiter.c) | Applies a function to the content of each element in a list. |
| [`ft_lstmap`](libft/ft_lstmap.c) | Creates a new list by applying a function to each element of an existing list. |

## Building the Library

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/jdecorte-be/libft.git
    cd libft
    ```

2.  **Compile the library:**
    The included `Makefile` provides several targets for building and managing the library.
    ```sh
    # Compiles source files and creates the static library libft.a
    make all

    # Removes object files (.o)
    make clean

    # Removes object files and the library file (libft.a)
    make fclean

    # Re-compiles the library from scratch
    make re
    ```

## Usage

1.  **Include the header** in your C source file:
    ```c
    #include "libft.h"
    ```

2.  **Compile your project** and link it with the `libft.a` library:
    ```sh
    # Example: Compiling main.c with libft
    gcc main.c -L. -lft -o my_program
    ```
    - `-L.` tells the compiler to look for libraries in the current directory.
    - `-lft` links the `libft` library.

## Contributing

If you find a bug or have a suggestion for improvement, please feel free to [open an issue](https://github.com/jdecorte-be/libft/issues). Pull requests are also welcome!

---

Give a ⭐️ if you found this project helpful
