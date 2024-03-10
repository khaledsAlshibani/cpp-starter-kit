<div align="center">
    <img src="./assets/thumbnail.png" alt="Thumbnail" height="120">
    <br>
    <h1>C++ Starter Kit - Learn Fundamentals</h1>
    <p>Here, you'll find beginner-friendly programs tutorials, essential data structures, algorithms, and file operations. All with C++.</p>
</div>

---

> Universities prefer teaching programming fundamentals using C++ due to its efficiency, versatility, industry relevance, support for object-oriented programming principles, emphasis on memory management, and its role as a transitional language. C++ provides students with a solid foundation in low-level concepts, such as memory management and pointers, while also preparing them for a wide range of industries and programming domains. Its widespread use in industries like game development, systems programming, and scientific computing ensures that students acquire skills that are highly sought after in the job market. Additionally, C++ serves as a stepping stone for learning other languages, making it an ideal choice for introducing students to the core principles of programming.
> ([ChatGPT](https://chat.openai.com/share/b0cb4eda-0f9d-4b3b-aba1-d6887f08d3ac))

## What's Inside?

- **Overview**
  - Why starting programming with c++
  - Using C++ with VS Code

- **Basic C++ Tutorials**
  - data types & variables
  - input/output (cin/cout)
  - control structures
  - functions
  - operators
  
- **Advanced C++ Concepts**
  - pointers
  - references
  - memory management
  
- **Data Structures**
  - arrays, 
  - linked lists
  - stacks
  - queues
  - trees
  - graphs

- **Object-Oriented Programming (OOP)**
  - inheritance
  - encapsulation
  - abstraction
  - polymorphism
  - template usage

- **File Handling and Strings**
  - read from files
  - write to files
  - manipulate strings
  - work with string streams

- **Standard Template Library (STL)**

- **Debugging Techniques**

## Overview

### Why starting programming with c++
C++ is a middle-level programming language, positioned between high-level languages like Python add javaScript and low-level languages like Assembly. It inherits features from both. C++ has the ability to perform low-level operations like memory management, similar to the C language. This makes it a suitable choice for understanding these operations, especially since it is not as difficult to learn as C or other low-level languages. Additionally, C++ provides high-level features such as object-oriented programming (OOP) as well as standard library support for data structures and algorithms.

### Using C++ with VS Code
To use C++ with VS Code, you'll need a compiler. By default, VS Code doesn't support C++ compilers, so you must install one such as GCC. There are various methods to set this up, including using the Mingw-w64 executable or the MSYS2 command-line interface (CLI). See this resource:
- [Setting up MinGW for C++ Development in Visual Studio Code](https://code.visualstudio.com/docs/cpp/config-mingw)

## Basic C++ Tutorials

### Data Types

Data types exist in all programming languages, although there may be small differences between them. For example, in C++, number data types include int, float, and double, while in TypeScript, there's only the number data type for numbers. Data types define the kind of data that a variable can hold, such as integers, floating point numbers, characters, and more. Here are the basic data types in C++:

| Data Type | Description                                     | Size/Length  |
| --------- | ----------------------------------------------- | ------------ |
| `int`     | Used for integers                               | 2 or 4 bytes |
| `float`   | Used for floating point numbers                 | 4 bytes      |
| `double`  | Used for double sized floating point numbers    | 8 bytes      |
| `char`    | Used for single characters                      | 1 byte       |
| `bool`    | Used for boolean values (true/false)            | 1 byte       |
| `auto`    | Automatically detects data type (C++11 version) | Variable     |

#### Example

```cpp
// datatype variableName = value;
int x = 5;
char c = 'A';
bool isDone = true;
auto y = x; // int
```

#### Resources
- [W3Schools - C++ Data Types](https://www.w3schools.com/cpp/cpp_data_types.asp)

### Basic Input and Output with `cin` and `cout`
In C++, the standard library `iostream` is commonly included in most `.cpp` files to control input and output operations.

The `cin` object, along with the `>>` extraction operator, is utilized for input operations. It allows users to input data from the console into variables. On the other hand, the `cout` object, paired with the `<<` insertion operator, is used for output operations and displaying data on the console.

It's important to note that when interacting with `cin`, input values should not contain spaces, as a space typically signifies the end of an input task. To input an entire line of text, the `getline` function can be used, which will be introduced later.

Additionally, the `cerr` and `clog` objects of the `iostream` library classes, they are used for error and logging purposes.

#### Example

```cpp
// Declare an integer variable to store the user's input
int number;

// Display a prompt for the user to enter a number
cout << "Enter a number: ";

// Read the user's input from the console and store it in the 'number' variable
cin >> number;

// Display the entered number 
cout << "The number is: " << number << endl;
```

#### Resources 
- (Basic Input / Output in C++)[https://www.geeksforgeeks.org/basic-input-output-c/]
- (Understanding the Concept of Cin Object in C++ for Beginners)[https://www.simplilearn.com/tutorials/cpp-tutorial/cpp-cin#:~:text=The%20C%2B%2B%20cin%20is%20an,extraction%20operator%20(%3E%3E).]
- (Difference between cerr and clog)[https://www.geeksforgeeks.org/difference-between-cerr-and-clog/]