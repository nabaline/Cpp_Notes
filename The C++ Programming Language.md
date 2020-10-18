# The C++ Programming Language:
## By: Madelyn Zamenski

### Introduction to C++:
C++ (Pronounced see plus plus) was developed by Bjarne Stroustrup at Bell Labs as an extension to C starting in 1979. C++'s claim to fame primarily results from the fact that it is an object-orientated language.

#### Hello World:
```
#include <iostream>

int main()
{
    std::cout << "Hello, World!";
    return 0;
}
```

### Statements:
A statement is a type of instruction that causes the program to perform some action. Statements are by far the most common type of instruction in a C++ program. In C++, when we want to have our program do something, we typically write statements. Every statement ends with a semicolon.

### Functions And The Main Function:
In C++, statements are typically grouped into functions. A function is a collection of statements that execute sequentially. Every C++ must have a special function named main.

### Dissecting Hello World:
Line 1 is a special type of line called the preprocessor directive. The preprocessor directive is similar to `import` in Java/Python/Etc. Line 2 is blank and is ignored by the compiler. It is only used for decoration purposes. Line 3 is the main function. Everything contained in the main function is contained within squiggly brackets. Line 5 is the first statement within the function main. std::cout (which stands for character output) and the << operator allows us to send letters or numbers to the console to be output. Line 6 is the return statement. When the program finishes executing, it will either return 0 or 1. 0 means everything went well while 1 means an error has occurred.




