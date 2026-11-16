*This project has been created as part of the 42 curriculum by toafonso.*

# libft

## Description

My first library in C. It has my own versions of some libc functions, plus other functions for strings, memory, output and linked lists that I will use in the next 42 projects.

## Instructions

Compile the library:

```
make
```

Other rules:
- make clean: removes the object files
- make fclean: removes the object files and libft.a
- make re: compiles everything again

To use it in a program, include libft.h and compile with:

```
cc main.c -L. -lft
```

## Functions

### Part 1 - Libc functions
- ft_isalpha: checks if a character is a letter
- ft_isdigit: checks if a character is a digit
- ft_isalnum: checks if a character is a letter or a digit
- ft_isascii: checks if a character is ASCII
- ft_isprint: checks if a character is printable
- ft_strlen: returns the length of a string
- ft_memset: fills memory with a byte
- ft_bzero: fills memory with zeros
- ft_memcpy: copies memory
- ft_memmove: copies memory, works when the areas overlap
- ft_strlcpy: copies a string with a size limit
- ft_strlcat: joins two strings with a size limit
- ft_toupper: converts to uppercase
- ft_tolower: converts to lowercase
- ft_strchr: finds the first occurrence of a character
- ft_strrchr: finds the last occurrence of a character
- ft_strncmp: compares two strings up to n characters
- ft_memchr: finds a byte in memory
- ft_memcmp: compares two memory areas
- ft_strnstr: finds a string inside another
- ft_atoi: converts a string to an int
- ft_calloc: allocates memory set to zero
- ft_strdup: duplicates a string

### Part 2 - Additional functions
- ft_substr: returns part of a string
- ft_strjoin: joins two strings into a new one
- ft_strtrim: removes characters from the start and end of a string
- ft_split: splits a string by a character
- ft_itoa: converts an int to a string
- ft_strmapi: applies a function to each character and returns a new string
- ft_striteri: applies a function to each character of the string
- ft_putchar_fd: writes a character to a file descriptor
- ft_putstr_fd: writes a string to a file descriptor
- ft_putendl_fd: writes a string and a newline to a file descriptor
- ft_putnbr_fd: writes a number to a file descriptor

### Part 3 - Linked lists
- ft_lstnew: creates a new node
- ft_lstadd_front: adds a node at the start of the list
- ft_lstsize: counts the nodes of the list
- ft_lstlast: returns the last node
- ft_lstadd_back: adds a node at the end of the list
- ft_lstdelone: frees one node
- ft_lstclear: frees the whole list
- ft_lstiter: applies a function to each node
- ft_lstmap: creates a new list by applying a function to each node

## Resources

- man pages of the libc functions
- 42 subject and norm

I used AI to understand some concepts (Makefile, pointers, linked lists). All the functions were written by me.
