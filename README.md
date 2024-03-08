<div align="center">
    <img src="./assets/thumbnail.png" alt="Thumbnail" height="160">
    <br>
    <h1>C++ Starter Kit</h1>
    <p>Here, you'll find beginner-friendly programs tutorials, essential data structures, algorithms, and file operations. All with C++.</p>
</div>

---

> "C++ is the most used language among competitive programmers because it provides many ready-to-use data structures, is very fast to execute, and also provides the programmer with control of the finest details of the program, which if used cleverly, can allow for creating very creative and efficient solutions."
> ([Hub21](https://thehub21.com/blog/20/why-should-children-learn-c))

## What's Inside?

- **Overview**
  - Why starting programming with c++
  - Using C++ with VS Code

- **Basic C++ Tutorials**
  - data types
  - input/output
  - variables
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

| Data Type      | Description                                      | Size/Length |
|----------------|--------------------------------------------------|-------------|
| `int`          | Used for integers                                | 2 or 4 bytes|
| `float`        | Used for floating point numbers                  | 4 bytes     |
| `double`       | Used for double sized floating point numbers     | 8 bytes     |
| `char`         | Used for single characters                       | 1 byte      |
| `bool`         | Used for boolean values (true/false)             | 1 byte      |
| `auto`         | Automatically detects data type (C++11 version)  | Variable    |

#### Usage

```cpp
// datatype variableName = value;
int x = 5;
```

#### Resources
- [W3Schools - C++ Data Types](https://www.w3schools.com/cpp/cpp_data_types.asp)
