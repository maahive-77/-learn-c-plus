---
## C++ 
C++ is a widely used Object Oriented Programming language and is fairly easy to understand.
Learning  C++ programming can be simplified into -   

Writing your program in a text editor and saving it with correct extension(.CPP, .C, .CP).
Compiling your program using a compiler or online IDE
Understanding the basic terminologies.

 
The "Hello World" program is the first step towards learning any programming language and is also one of the simplest programs you will learn.

--- 
## 1) // C++ program to display "Hello World": 
This line is a comment line. A comment is used to display additional information about the program. A comment does not contain any programming logic. When a comment is encountered by a compiler, the compiler simply skips that line of code. Any line beginning with '//' without quotes OR in between /*...*/ in C++ is comment. 
 

## 2) #include:
In C++,  all lines that start with pound (#) sign are called directives and are processed by a preprocessor which is a program invoked by the compiler. The #include directive tells the compiler to include a file and #include<iostream>. It tells the compiler to include the standard iostream file which contains declarations of all the standard input/output library functions.

## 3) using namespace std: 
This is used to import the entirety of the std namespace into the current namespace of the program. The statement using namespace std is generally considered a bad practice. When we import a namespace we are essentially pulling all type definitions into the current scope. The std namespace is huge. The alternative to this statement is to specify the namespace to which the identifier belongs using the scope operator(::) each time we declare a type.

## 4) int main(): 
This line is used to declare a function named "main" which returns data of integer type. A function is a group of statements that are designed to perform a specific task. Execution of every C++ program begins with the main() function, no matter where the function is located in the program. So, every C++ program must have a main() function. 

## 5) { and }:
The opening braces '{' indicates the beginning of the main function and the closing braces '}' indicates the ending of the main function. Everything between these two comprises the body of the main function.

## 6) std::cout<<"Hello World";: 
This line tells the compiler to display the message "Hello World" on the screen. This line is called a statement in C++. Every statement is meant to perform some task. A semi-colon ';' is used to end a statement. Semi-colon character at the end of the statement is used to indicate that the statement is ending there. The std::cout is used to identify the standard character output device which is usually the desktop screen. Everything followed by the character "<<" is displayed to the output device.

## 7) return 0; :
This is also a statement. This statement is used to return a value from a function and indicates the finishing of a function. This statement is basically used in functions to return the results of the operations performed by a function. 

## 8) Indentation:
As you can see the cout and the return statement have been indented or moved to the right side. This is done to make the code more readable. In a program as Hello World, it does not hold much relevance, but as the programs become more complex, it makes the code more readable, less error-prone. Therefore, you must always use indentations and comments to make the code more readable. 

 ---

## Important Points to Note while Writing a C++ Program:

Always include the necessary header files for the smooth execution of functions.
For example, <iostream> must be included to use std::cin and std::cout.
The execution of code begins from the main() function.
It is a good practice to use Indentation and comments in programs for easy understanding.
cout is used to print statements and cin is used to take inputs.
