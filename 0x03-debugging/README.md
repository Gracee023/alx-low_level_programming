0x03. C - Debugging

Resources
Read or watch:

Debugging
Rubber Duck Debugging
Debugging is the process of finding and fixing errors in software that prevents it from running correctly. As you become a more advanced programmer and an industry engineer, you will learn how to use debugging tools such as gdb or built-in tools that IDEs have. However, it’s important to understand the concepts and processes of debugging manually.

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is debugging
What are some methods of debugging manually
How to read the error messages

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
A README.md file at the root of the repo, containing a description of the repository
A README.md file, at the root of the folder of this project (i.e. 0x03-debugging), describing what this project is about

Tasks
0. Multiple mains
mandatory
Score: 87.5% (Checks completed: 87.5%)
In most projects, we often give you only one main file to test with. For example, this main file is a test for a postitive_or_negative() function similar to the one you worked with in an earlier C project:

Based on the main.c file above, create a file named 0-main.c. This file must test that the function positive_or_negative() gives the correct output when given a case of 0.

You are not coding the solution / function, you’re just testing it! However, you can adapt your function from 0x01. C - Variables, if, else, while - Task #0 to compile with this main file to test locally.

You only need to upload 0-main.c and main.h for this task. We will provide our own positive_or_negative() function.
You are not allowed to add or remove lines of code, you may change only one line in this task.

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x03-debugging
File: 0-main.c, main.h

1. Like, comment, subscribe
mandatory
Score: 88.89% (Checks completed: 88.89%)
Copy this main file. Comment out (don’t delete it!) the part of the code that is causing the output to go into an infinite loop.

Don’t add or remove any lines of code, as we will be checking your line count. You are only allowed to comment out existing code.
You do not have to compile with -Wall -Werror -Wextra -pedantic for this task.

Repo:

GitHub repository: alx-low_level_programming
Directory: 0x03-debugging
File: 1-main.c

2. 0 > 972?
mandatory
Score: 100.0% (Checks completed: 100.0%)
This program prints the largest of three integers.

? That’s definitely not right.

Fix the code in 2-largest_number.c so that it correctly prints out the largest of three numbers, no matter the case.

Line count will not be checked for this task.

3. Leap year
mandatory
Score: 100.0% (Checks completed: 100.0%)
This program converts a date to the day of year and determines how many days are left in the year, taking leap year into consideration.
Repo:

GitHub repository: alx-low_level_programming
Directory: 0x03-debugging
File: 3-print_remaining_days.c, main.h
