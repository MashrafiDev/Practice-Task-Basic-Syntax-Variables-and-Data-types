#Practice Task of Basic Syntax, Variables and Data Types
---

1. Explain why we need long long int data type?
2. Write all the rules for naming a variable in C programming.
3. Write a C program that will take 2 numbers from the user and then print the 2nd number first and then first number.  

---

Answer: 

1: We need the `long long int` data type when we need to store integer values that exceed the memory space of a regular `int`. Typically, a `long long int` uses 64 bits, which allows it to store much larger numbers compared to an `int` (which generally uses 32 bits).

---

2:-
 1. A variable must start with a letter (a-z, A-Z) or an underscore (`_`).
 2. The rest of the variable name can include letters, numbers (0-9), or underscores (`_`).
 3. Variable names are **case-sensitive** in C, meaning `variable`, `Variable`, and `VARIABLE` are considered different.
 4. A variable name **cannot** be a C keyword (such as `int`, `for`, `return`, etc.).
 5. Variable names should be meaningful and descriptive for better code readability (e.g., `age`, `totalPrice`).
 6. A variable name should not exceed the maximum length allowed by the compiler (although this is typically quite large).
 7. Variable names **cannot** contain spaces.
---

3: Go to the practice.c file >