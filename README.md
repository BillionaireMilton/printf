printf
The printf project is a collaboration between Milton Jesumbo Arogbofa and Gbemisola Olaniyan, students of Software Engineering at ALX.


#Welcome
Rebuild the standard printf function in C. Our project requires a function capable of printing with the %d, %c, %s, and %% specifiers to standard output. printf returns the number of characters printed (excluding the null byte at the end of strings). We were not asked to handle flag characters, field width, precision, or length.

This function named "_printf()" imitates the actual "printf()" command located in the stdio.h library of C programming Language. It contains some of the basic features and functions found in the manual 3 of "printf".
_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:
 int _printf(const char *format, ...) 
Where format contains the string that is printed.
_printf() is a variadic function, it can receives n arguments that replace by n tags written inside the string.
The format tags prototype is the following:
%[flags][length]specifier
If the program runs successfully, the return value is the amount of chars printed.

#Format Specifiers
Our team chose to add %x,%X, %b, %o, %u, %r, %R, and %p formatting. We relied on the library we have been building at Alx as well as new concepts gathered during this project.

#Supported Format Types
TYPE - OUTPUT
c - Single character
s - String
r - String in reverse
R - String in rot13
d - Integer in decimal
i - integer
% - Percent sign
Xl - Lowercase hex
X - Uppercase hex
b - binary
o - octal
u - unsigned
p - pointer
F - expletive

#Examples
Character: printf("%c", A); Output:: A
String: printf("%s", This is a string.); Output: This is a string.
Integer: printf("%i", 5); Output: 5
Expletive: printf("%F", anything); Output: FRIEND

#Requirements
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions should be included in your header file called main.h
Don’t forget to push your header file
All your header files should be include guarded
Note that we will not provide the _putchar function for this project


Authors
Milton Jesumbo Arogbofa and Gbemisola Olaniyan