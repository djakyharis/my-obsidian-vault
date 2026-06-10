---
date: 2026-01-31 14:30
status: growing
tags: [c-language, computer-science]
source: Self-study / W3Schools
---

# C User Input

## `scanf()` Function

`scanf()` is used to get user input. It takes two arguments: the **format specifier** and the **reference operator** (`&variable`) which stores the memory address of the variable.

![[_assets/Pasted image 20260131143743.png]]

![[_assets/Pasted image 20260131145027.png]]

When working with strings in `scanf()`, specify the size of the string/array and you don't need the reference operator (`&`):

![[_assets/Pasted image 20260131145151.png]]

> **Rule of thumb**: Use `scanf()` for a **single word**, use `fgets()` for **multiple words**.

## Related
- [[C Learning Roadmap]]
- [[C Language]]
- [[C Pointer]]
- [[Memory Address in C]]

## References
- W3Schools C Tutorial
