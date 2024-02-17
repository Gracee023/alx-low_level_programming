0x04. C - More functions, more nested loops

Resources
Read or watch:

Nested while loops
C - Functions
Learning to Program in C (Part 06) (stop at 14:00)
What is the purpose of a function prototype?
C - Header Files (stop before the “Once-Only Headers” paragraph)
Additional Resources
Functions in C programming
Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What are nested loops and how to use them
What is a function and how do you use functions
What is the difference between a declaration and a definition of a function
What is a prototype
Scope of variables
What are the gcc flags -Wall -Werror -pedantic -Wextra -std=gnu89
What are header files and how to to use them with #include

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
You are not allowed to use the standard library. Any use of functions like printf, puts, etc… is forbidden
You are allowed to use _putchar
You don’t have to push _putchar.c, we will use our file. If you do it won’t be taken into account
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions and the prototype of the function _putchar should be included in your header file called main.h
Don’t forget to push your header file
More Info
You do not have to understand the call by reference (address), stack, static variables, recursions or arrays, yet.

Quiz questions
Great! You've completed the quiz successfully! Keep going! (Show quiz)
Tasks
0. isupper
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that checks for uppercase character.

Prototype: int _isupper(int c);
Returns 1 if c is uppercase
Returns 0 otherwise
FYI: The standard library provides a similar function: isupper. Run man isupper to learn more.

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 0-isupper.c
    
1. isdigit
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that checks for a digit (0 through 9).

Prototype: int _isdigit(int c);
Returns 1 if c is a digit
Returns 0 otherwise
FYI: The standard library provides a similar function: isdigit. Run man isdigit to learn more.

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 1-isdigit.c
    
2. Collaboration is multiplication
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that multiplies two integers.

Prototype: int mul(int a, int b);

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 2-mul.c
    
3. The numbers speak for themselves
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints the numbers, from 0 to 9, followed by a new line.

Prototype: void print_numbers(void);
You can only use _putchar twice in your code

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 3-print_numbers.c
    
4. I believe in numbers and signs
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints the numbers, from 0 to 9, followed by a new line.

Prototype: void print_most_numbers(void);
Do not print 2 and 4
You can only use _putchar twice in your code

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 4-print_most_numbers.c
    
5. Numbers constitute the only universal language
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints 10 times the numbers, from 0 to 14, followed by a new line.

Prototype: void more_numbers(void);
You can only use _putchar three times in your code

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 5-more_numbers.c
    
6. The shortest distance between two points is a straight line
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that draws a straight line in the terminal.

Prototype: void print_line(int n);
You can only use _putchar function to print
Where n is the number of times the character _ should be printed
The line should end with a \n
If n is 0 or less, the function should only print \n

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 5-more_numbers.c
    
Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 7-print_diagonal.c
    
8. You are so much sunshine in every square inch
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints a square, followed by a new line.

Prototype: void print_square(int size);
You can only use _putchar function to print
Where size is the size of the square
If size is 0 or less, the function should print only a new line
Use the character # to print the square

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 8-print_square.c
    
9. Fizz-Buzz
mandatory
Score: 100.0% (Checks completed: 100.0%)
The “Fizz-Buzz test” is an interview question designed to help filter out the 99.5% of programming job candidates who can’t seem to program their way out of a wet paper bag.

Write a program that prints the numbers from 1 to 100, followed by a new line. But for multiples of three print Fizz instead of the number and for the multiples of five print Buzz. For numbers which are multiples of both three and five print FizzBuzz.

Each number or word should be separated by a space
You are allowed to use the standard library

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 9-fizz_buzz.c
    
10. Triangles
mandatory
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints a triangle, followed by a new line.

Prototype: void print_triangle(int size);
You can only use _putchar function to print
Where size is the size of the triangle
If size is 0 or less, the function should print only a new line
Use the character # to print the triangle

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 10-print_triangle.c
    
11. The problem of distinguishing prime numbers from composite numbers and of resolving the latter into their prime factors is known to be one of the most important and useful in arithmetic
#advanced
Score: 100.0% (Checks completed: 100.0%)
The prime factors of 1231952 are 2, 2, 2, 2, 37 and 2081.

Write a program that finds and prints the largest prime factor of the number 612852475143, followed by a new line.

You are allowed to use the standard library
Your program will be compiled with this command: gcc -Wall -pedantic -Werror -Wextra -std=gnu89 100-prime_factor.c -o 100-prime_factor -lm
Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 100-prime_factor.c
    
12. Numbers have life; they're not just symbols on paper
#advanced
Score: 100.0% (Checks completed: 100.0%)
Write a function that prints an integer.

Prototype: void print_number(int n);
You can only use _putchar function to print
You are not allowed to use long
You are not allowed to use arrays or pointers
You are not allowed to hard-code special values

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x04-more_functions_nested_loops
File: 101-print_number.c


