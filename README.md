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
<a href="https://www.42.fr/">
    <img src="https://img.shields.io/badge/42%20School-Project-00B8BB?logo=42&logoColor=white&labelColor=000000"
         alt="42 School Project">
  </a>
<a href="#">
    <img src="https://img.shields.io/badge/Focus-System%20Programming-555555?logo=c&logoColor=white&labelColor=000000"
         alt="Focus System Programming">
  </a>
<a href="#">
    <img src="https://img.shields.io/badge/Type-Static%20Library-007EC6?logo=c&logoColor=white&labelColor=000000"
         alt="Type Static Library">
  </a>
<a href="#">
    <img src="https://img.shields.io/badge/Platform-macOS%20%7C%20Linux-lightgrey?logo=apple&logoColor=white&labelColor=000000"
         alt="Platform macOS | Linux">
  </a>
</p>

<p align="center">
<a href="#">
    <img src="https://img.shields.io/badge/Standard-libc-A42E2B?logo=c&logoColor=white&labelColor=000000"
         alt="Standard libc">
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

<!-- README_HEADER_START -->
<header>
<h1 align="center">
  <a href="https://github.com/jdecorte-be/42-libft"><img src=".assets/banner.png" alt="42-libft" ></a>
  42-libft
  <br>
</h1>

  <p align="center">My own library of useful functions in C.</p>

<p align="center">
  <a href="https://github.com/jdecorte-be/42-libft">
    <img src="https://shields.io/github/stars/jdecorte-be/42-libft?logo=star&logoColor=white&labelColor=000000&color=yellow" alt="42-libft badge">
  </a>
  <a href="https://github.com/jdecorte-be/42-libft">
    <img src="https://shields.io/github/issues/jdecorte-be/42-libft?logoColor=white&labelColor=000000&color=orange" alt="42-libft badge">
  </a>
  <a href="https://github.com/jdecorte-be/42-libft">
    <img src="https://shields.io/github/repo-size/jdecorte-be/42-libft?logo=database&logoColor=white&labelColor=000000&color=purple" alt="42-libft badge">
  </a>
  <a href="https://github.com/jdecorte-be/42-libft">
    <img src="https://shields.io/github/languages/top/jdecorte-be/42-libft?logo=code&logoColor=white&labelColor=000000&color=green" alt="42-libft badge">
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
<!-- README_HEADER_END -->

# :pushpin: Index

* [What's this Repo?](#sparkles-What-is-Libft?)
* [List of Functions](#bookmark_tabs-List-of-Fucntions)
* [Technologies](#computer-Technologies)
* [How to Run](#construction_worker-How-to-Run)
* [Find a Bug? Or somenthing need to change?](#bug-Issues)

# :sparkles: What is Libft?

Libft is an individual project at 42 that requires us to re-create some standard C library functions including some additional ones that can be used later to build a library of useful functions for the rest of the program.

At 42 we're not allowed to use some standard libraries on our projects, so we have to keep growing this library with our own functions as we go farther in the program.

---

# :bookmark_tabs: List of Fucntions

## Functions from `<ctype.h>`

- [x] [`ft_isalpha`](ft_isalpha.c)	- checks for an alphabetic character.
- [x] [`ft_isdigit`](ft_isdigit.c)	- check for a digit (0 through 9).
- [x] [`ft_isalnum`](ft_isalnum.c)	- checks for an alphanumeric character.
- [x] [`ft_isascii`](ft_isascii.c)	- checks whether c fits into the ASCII character set.
- [x] [`ft_isprint`](ft_isprint.c)	- checks for any printable character.
- [x] [`ft_toupper`](ft_toupper.c)	- convert char to uppercase.
- [x] [`ft_tolower`](ft_tolower.c)	- convert char to lowercase.

## Functions from `<string.h>`

- [x] [`ft_strlen`](ft_strlen.c)	- calculate the length of a string.
- [x] [`ft_memset`](ft_memset.c)	- fill memory with a constant byte.
- [x] [`ft_bzero`](ft_bzero.c)	- zero a byte string.
- [x] [`ft_memcpy`](ft_memcpy.c)	- copy memory area.
- [x] [`ft_memmove`](ft_memmove.c)	- copy memory area.
- [x] [`ft_strlcpy`](ft_strlcpy.c)	- copy string to a specific size.
- [x] [`ft_strlcat`](ft_strlcat.c)	- concatenate a string to a specific size.
- [x] [`ft_strchr`](ft_strchr.c)	- locate character in a string.
- [x] [`ft_strrchr`](ft_strrchr.c)	- locate character in a string.
- [x] [`ft_strncmp`](ft_strncmp.c)	- compare two strings.
- [x] [`ft_memchr`](ft_memchr.c)	- scan memory for a character.
- [x] [`ft_memcmp`](ft_memcmp.c)	- compare memory areas.
- [x] [`ft_strnstr`](ft_strnstr.c)	- locate a substring in a string.
- [x] [`ft_strdup`](ft_strdup.c)	- creates a duplicate for the string passed as a parameter.

## Functions from `<stdlib.h>`
- [x] [`ft_atoi`](ft_atoi.c)	- convert a string to an integer.
- [x] [`ft_calloc`](ft_calloc.c)	- allocates memory and sets its bytes' values to 0.

## Non-standard functions
- [x] [`ft_substr`](ft_substr.c)	- returns a substring from a string.
- [x] [`ft_strjoin`](ft_strjoin.c)	- concatenates two strings.
- [x] [`ft_strtrim`](ft_strtrim.c)	- trims the beginning and end of a string with a specific set of chars.
- [x] [`ft_split`](ft_split.c)	- splits a string using a char as parameter.
- [x] [`ft_itoa`](ft_itoa.c)	- converts a number into a string.
- [x] [`ft_strmapi`](ft_strmapi.c)	- applies a function to each character of a string.
- [x] [`ft_striteri`](ft_striteri.c)	- applies a function to each character of a string.
- [x] [`ft_putchar_fd`](ft_putchar_fd.c)	- output a char to a file descriptor.
- [x] [`ft_putstr_fd`](ft_putstr_fd.c)	- output a string to a file descriptor.
- [x] [`ft_putendl_fd`](ft_putendl_fd.c)	- output a string to a file descriptor, followed by a new line.
- [x] [`ft_putnbr_fd`](ft_putnbr_fd.c)	- output a number to a file descriptor.

## Linked list functions

- [x] [`ft_lstnew`](ft_lstnew.c)	- creates a new list element.
- [x] [`ft_lstadd_front`](ft_lstadd_front.c)	- adds an element at the beginning of a list.
- [x] [`ft_lstsize`](ft_lstsize.c)	- counts the number of elements in a list.
- [x] [`ft_lstlast`](ft_lstlast.c)	- returns the last element of the list.
- [x] [`ft_lstadd_back`](ft_lstadd_back.c)	- adds an element at the end of a list.
- [x] [`ft_lstclear`](ft_lstclear.c)	- deletes and free list.
- [x] [`ft_lstiter`](ft_lstiter.c)	- applies a function to each element of a list.
- [x] [`ft_lstmap`](ft_lstmap.c)	- applies a function to each element of a list.

---

# :computer: Technologies

This Project was made with:

* [C](https://devdocs.io/)
* [Makefile](https://www.gnu.org/software/make/manual/make.html)
* [Shell](https://unixguide.readthedocs.io/en/latest/unixcheatsheet/)
* [gcc](https://terminaldeinformacao.com/2015/10/08/como-instalar-e-configurar-o-gcc-no-windows-mingw/)

# :construction_worker: How to Run
```bash
# *************COMMANDS************ #
# run - run compile all the libtest with the your libft and run the all tests
$ make all
# clean - remove the .o and .c files 
$ make clean
# fclean - remove the .o and .c files and the .a
$ make fclean
# re - remove all files and remake all
$ make re

# after run one time the the comand all 
# you can use compile others files .c using this lib 
# and using the function of then.
$ gcc main.c -L . -lft

```


# :bug: Issues

Please feel free **to create a new issue** with its title and description on the issues page of the [Libft](https://github.com/jdecorte-be/42-Libft/issues) Repository. If you have already found the solution to the problem, **I would love to review your pull request**!


Give ⭐️ if you like this project, this will help me!
