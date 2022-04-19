Printf

Description

The _printf() function produces output according to a format which is described below. This function write its output to the stdout, the standard output. Returns the count of printed characters when the function is successful The available convertion specifiers are:



%c: Prints a single character.

%s: Prints a string of characters.

%d: Prints integers.

%i: Prints integers.

%b: Prints the binary representation of an unsigned decimal.

%u: Prints unsigned integers

%x: Prints the hexadecial representation of an unsigned decimal in lowercase letters

%X:Prints the hexadecial representation of an unsigned decimal in uppercase letters

%r: Prints a reversed string

Usag

All the files are to be compiled on Ubuntu 20.04 LTS using gcc, using the options  gcc -Wall -Wextra -Werror -pedantic -std=gnu89 -Wno-format *.c

Include the "main.h" header file on the functions using the _printf()

This is a group project by Mofu Bulaya and Sesugh Nanakaan