
# Conditional Statements in C

This repository provides a comprehensive guide to **Conditional Statements in C**, a fundamental concept that allows developers to make decisions in their programs based on certain conditions.

---

## Table of Contents

- [Overview](#overview)
- [Why Conditional Statements Are Important](#why-conditional-statements-are-important)
- [Types of Conditional Statements in C](#types-of-conditional-statements-in-c)
  - [1. if Statement](#1-if-statement)
  - [2. if-else Statement](#2-if-else-statement)
  - [3. if-else-if Ladder](#3-if-else-if-ladder)
  - [4. Nested if Statement](#4-nested-if-statement)
  - [5. switch Statement](#5-switch-statement)
- [Examples](#examples)
- [Practice Exercises](#practice-exercises)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Conditional statements in C are used to perform different actions based on specific conditions. They enable decision-making and control the flow of a program.

For example, if a condition is true, a block of code will execute; otherwise, another block may execute.

---

## Why Conditional Statements Are Important

1. **Decision-Making**: Enables programs to adapt based on input or conditions.
2. **Logic Implementation**: Essential for implementing algorithms.
3. **Flow Control**: Controls which part of the code executes in various scenarios.

---

## Types of Conditional Statements in C

### 1. `if` Statement
The simplest form of a conditional statement. Executes a block of code if the condition is true.

Syntax:
```c
if (condition) {
    // Code to execute if the condition is true
}
```

---

### 2. `if-else` Statement
Executes one block of code if the condition is true and another if it is false.

Syntax:
```c
if (condition) {
    // Code to execute if the condition is true
} else {
    // Code to execute if the condition is false
}
```

---

### 3. `if-else-if` Ladder
Used to test multiple conditions sequentially.

Syntax:
```c
if (condition1) {
    // Code for condition1
} else if (condition2) {
    // Code for condition2
} else {
    // Code if none of the conditions are true
}
```

---

### 4. Nested `if` Statement
An `if` statement inside another `if` statement.

Syntax:
```c
if (condition1) {
    if (condition2) {
        // Code for condition1 and condition2
    }
}
```

---

### 5. `switch` Statement
Tests a variable against multiple values and executes the corresponding block.

Syntax:
```c
switch (expression) {
    case value1:
        // Code for value1
        break;
    case value2:
        // Code for value2
        break;
    default:
        // Code if none of the cases match
}
```

---

## Examples

### Example 1: Using `if`
```c
#include <stdio.h>
int main() {
    int number = 10;
    if (number > 0) {
        printf("The number is positive.
");
    }
    return 0;
}
```

### Example 2: Using `if-else`
```c
#include <stdio.h>
int main() {
    int number = -5;
    if (number > 0) {
        printf("The number is positive.
");
    } else {
        printf("The number is not positive.
");
    }
    return 0;
}
```

### Example 3: Using `switch`
```c
#include <stdio.h>
int main() {
    int choice = 2;
    switch (choice) {
        case 1:
            printf("Option 1 selected.
");
            break;
        case 2:
            printf("Option 2 selected.
");
            break;
        default:
            printf("Invalid option.
");
    }
    return 0;
}
```

---

## Practice Exercises

1. Write a program to check if a number is even or odd.
2. Create a program that takes a user's grade (A, B, C, etc.) and prints a message using the `switch` statement.
3. Write a program to find the largest of three numbers using nested `if`.
4. Build a simple calculator using the `switch` statement to perform basic operations like addition, subtraction, multiplication, and division.

---

## Resources

- [GeeksforGeeks - Conditional Statements in C](https://www.geeksforgeeks.org/decision-making-c-c/)
- [TutorialsPoint - C Conditions](https://www.tutorialspoint.com/cprogramming/c_decision_making.htm)
- [Programiz - C Conditional Statements](https://www.programiz.com/c-programming/c-if-else)

---

## Contributing

Contributions are welcome! If you have suggestions, examples, or additional exercises, feel free to:

1. Fork the repository.
2. Create a branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Happy Coding! 🎉
