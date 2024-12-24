# Data Types in C Programming Language

This repository is a beginner-friendly guide to understanding **data types in C**, one of the fundamental concepts of the language. Data types define the type of data that variables can store, which is essential for memory allocation and program functionality.

---

## Table of Contents

- [Overview](#overview)
- [Why Data Types Are Important](#why-data-types-are-important)
- [Categories of Data Types](#categories-of-data-types)
- [Basic Data Types](#basic-data-types)
- [Derived Data Types](#derived-data-types)
- [Special Data Types](#special-data-types)
- [Examples](#examples)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

In C, every variable must be declared with a specific data type. This determines the type of data it can hold, its size, and the operations that can be performed on it. Understanding data types is a crucial step in mastering C programming.

---

## Why Data Types Are Important

1. **Memory Allocation**: Determines how much memory will be allocated for a variable.
2. **Efficiency**: Helps optimize program performance by using the appropriate type for the task.
3. **Error Prevention**: Ensures type safety and avoids logical errors.

---

## Categories of Data Types

C data types are broadly categorized into three types:

1. **Basic Data Types**: Built-in types such as integers, floating-point numbers, and characters.
2. **Derived Data Types**: Types created using basic types, including arrays, pointers, and structures.
3. **Special Data Types**: Includes enumerations (`enum`), type qualifiers, and the `void` type.

---

## Basic Data Types

| **Type**    | **Description**       | **Size (in bytes)**   | **Range**                        |
|-------------|-----------------------|-----------------------|-----------------------------------|
| `int`       | Integer               | 2 or 4               | -32,768 to 32,767 (2 bytes)      |
| `float`     | Floating-point number | 4                     | ±3.4e-38 to ±3.4e+38            |
| `double`    | Double precision float| 8                     | ±1.7e-308 to ±1.7e+308          |
| `char`      | Character             | 1                     | 0 to 255 (unsigned)             |
| `void`      | No data               | 0                     | N/A                              |

---

## Derived Data Types

### 1. **Arrays**
   - A collection of elements of the same data type.
   - Example: `int numbers[5];`

### 2. **Pointers**
   - Stores the address of another variable.
   - Example: `int *ptr;`

### 3. **Structures**
   - Groups variables of different data types under a single name.
   - Example:
     ```c
     struct Point {
         int x;
         int y;
     };
     ```

### 4. **Unions**
   - Similar to structures but shares memory among all members.
   - Example:
     ```c
     union Data {
         int i;
         float f;
     };
     ```

---

## Special Data Types

1. **Enumerations (`enum`)**: Used to define a set of named integral constants.
   ```c
   enum Color { RED, GREEN, BLUE };
