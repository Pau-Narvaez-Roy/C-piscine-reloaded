# C Piscine Reloaded

Welcome to the C Piscine Reloaded repository! This is a comprehensive refresher course covering fundamental and advanced C programming concepts through 28 hands-on exercises.

## 📑 Table of Contents

### Exercise Overview

| Range | Count | Focus Area |
|-------|-------|-----------|
| **ex00 - ex09** | 10 exercises | Fundamental Concepts |
| **ex10 - ex19** | 10 exercises | Intermediate Challenges |
| **ex20 - ex27** | 8 exercises | Advanced Topics |

**Total: 28 exercises** covering core C programming skills

---

## 📂 Exercise Breakdown

### 🔧 Fundamental Concepts (ex00-ex09)

**ex00** - Basic Program Structure
- Introduction to main function and program flow

**ex01** - Variable Declaration & Initialization
- Working with different data types and variable storage

**ex02** - Printing Output
- Using `printf()` and formatting output

**ex03** - Arithmetic Operations
- Basic mathematical operations and calculations

**ex04** - Control Flow - If/Else
- Conditional execution with if and else statements

**ex05** - Loops - While
- Iterating with while loops

**ex06** - Loops - For
- Iterating with for loops

**ex07** - String Basics
- Working with character arrays and strings

**ex08** - Arrays
- Array declaration, initialization, and iteration

**ex09** - Function Definition & Calling
- Creating and using custom functions

### 🎯 Intermediate Challenges (ex10-ex19)

**ex10** - Recursion Introduction
- Understanding recursive function calls and base cases

**ex11** - Pointer Fundamentals
- Address-of operator, dereferencing, and pointer arithmetic

**ex12** - String Functions
- String manipulation with functions like strlen, strcpy

**ex13** - Multi-dimensional Arrays
- Working with 2D and higher dimensional arrays

**ex14** - Pointers to Arrays
- Advanced pointer concepts with arrays

**ex15** - Dynamic Memory Allocation
- Using malloc() and managing heap memory

**ex16** - Structs Introduction
- Defining and using structures

**ex17** - Struct Pointers
- Working with pointers to structures

**ex18** - Union & Enum
- Advanced data types and enumeration

**ex19** - File I/O Basics
- Reading and writing files in C

### 🚀 Advanced Topics (ex20-ex27)

**ex20** - Advanced File I/O
- Binary files, file positioning, advanced techniques

**ex21** - Command Line Arguments
- Parsing argc and argv

**ex22** - Makefile Introduction
- Building projects with make

**ex23** - Preprocessor Directives
- #define, #include, conditional compilation

**ex24** - Bitwise Operations
- Bit manipulation and bitwise operators

**ex25** - Memory Management
- Advanced allocation, deallocation, and debugging

**ex26** - Linked Lists
- Dynamic data structures with pointers

**ex27** - Advanced Programming Patterns
- Complex algorithms and optimization techniques

---

## 🛠️ Technologies Used

- **C (91.5%)** - Core programming language
- **Makefile (8.2%)** - Build automation
- **Shell (0.3%)** - Build scripts

---

## 🚀 Getting Started

### Prerequisites
- GCC compiler (or compatible C compiler)
- Unix/Linux environment or WSL (Windows Subsystem for Linux)
- GNU Make (for Makefile exercises)
- Text editor or IDE (VSCode, Vim, etc.)

### Cloning the Repository

```bash
git clone https://github.com/Pau-Narvaez-Roy/C-piscine-reloaded.git
cd C-piscine-reloaded
```

### Compiling Exercises

#### Basic Compilation
```bash
cd ex00
gcc -o program program.c
./program
```

#### With Compiler Flags (42 School Standard)
```bash
gcc -Wall -Wextra -Werror -o program program.c
./program
```

#### Using Makefile (if available)
```bash
cd ex22
make
make clean
make fclean
```

---

## 📚 Recommended Learning Path

1. **Start with Fundamentals** (ex00-ex09)
   - Build a solid understanding of basic C syntax
   - Practice loops and conditionals
   - Get comfortable with functions

2. **Progress to Intermediate** (ex10-ex19)
   - Learn pointers and memory management
   - Work with data structures
   - Understand file I/O

3. **Challenge Yourself** (ex20-ex27)
   - Implement complex algorithms
   - Use build tools effectively
   - Master advanced techniques

---

## 💡 Tips & Best Practices

- **Compile frequently** - Don't wait until the end to test code
- **Use strict flags** - Compile with `-Wall -Wextra -Werror` to catch errors early
- **Test edge cases** - Always consider boundary conditions
- **Read error messages** - They point you to the problem
- **Use a debugger** - GDB can help you understand program flow
- **Follow the 42 norm** - Keep code clean and consistent
- **Practice, practice, practice** - Repetition builds mastery

### Debugging Tips
```bash
# Compile with debug symbols
gcc -g -Wall -Wextra -Werror -o program program.c

# Run with debugger
gdb ./program

# Or use valgrind for memory issues
valgrind --leak-check=full ./program
```

---

## 📝 Code Style Guidelines

This repository follows the 42 School Coding Norm:
- Maximum line length: 80 characters
- Proper indentation and spacing
- Meaningful variable names
- Functions should be small and focused

---

## 🔗 Resources

- [C Reference](https://en.cppreference.com/w/c) - Complete C reference
- [GDB Tutorial](https://www.gnu.org/software/gdb/documentation/) - Debugging guide
- [Make Tutorial](https://www.gnu.org/software/make/manual/) - Makefile documentation
- [Valgrind](https://valgrind.org/) - Memory debugging tool

---

## 👤 Author

**Pau Narváez Roy**

42 Student | [GitHub Profile](https://github.com/Pau-Narvaez-Roy)

---

## 📜 License

This project is part of the 42 school curriculum and follows their academic policies.

---

## 📌 Project Status

✅ **In Progress** - Continuously updating with solutions and improvements

---

**Last Updated:** May 24, 2026
