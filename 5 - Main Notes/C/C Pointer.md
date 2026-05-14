---
date: 2026-01-31 15:24
status: growing
tags: [c-language, computer-science]
source: Self-study / W3Schools
---

# C Pointer

A **pointer** is a variable that **stores** the **memory address** of another variable as its value.

A **pointer variable** **points** to a **data type** (like `int`) of the same type, and is created with the `*` operator.

```c
int myAge = 43;       // an int variable
int* ptr = &myAge;    // a pointer variable that stores the address of myAge

printf("%d\n", myAge);   // outputs the value of myAge (43)
printf("%p\n", &myAge);  // outputs the memory address of myAge
printf("%p\n", ptr);     // outputs the memory address of myAge with the pointer
```

## 🔗 Related
- [[Memory Address in C]]
- [[C Learning Roadmap]]
- [[C Language]]
- [[C user input]]

## References
- W3Schools C Tutorial
