---
date: 2026-01-13 15:19
status: growing
tags: [c-language, computer-science]
source: Self-study / W3Schools
---

# C Learning Roadmap

My personal roadmap for getting serious about low-level programming as a Computer Engineering student.

## Roadmap
1. Learn low level (C) ← *here now*
2. Learn Assembly
3. Reverse Engineering (bug hunting, etc.)
4. Learn to code microcontrollers (ESP32, Arduino, etc.) ← *skipped some steps but this too*

## Basics

`<stdio.h>` = standard input/output library (preprocessor directive)

`return 0;` = main function is expected to return an integer. `0` means the program ran successfully; anything else indicates an error.

`printf("text");` = print "text" to the console

`//` = single-line comment. `/* ... */` = multi-line comment

### Variables
A variable is a reusable container for a value. It behaves like the value it contains.

| Type | Description | Size | Example |
|---|---|---|---|
| `int` | Whole numbers | 4 bytes | `printf("%d", num);` |
| `float` | Single-precision decimal | 4 bytes | `printf("%.1f", temp);` |
| `double` | Double-precision decimal | 8 bytes | `printf("%.15lf", pi);` |
| `char` | Single character | 1 byte | `printf("%c", grade);` |
| `char[]` | Array of characters (string) | Varies | `printf("%s", name);` |
| `bool` | True or false (needs `<stdbool.h>`) | 1 byte | used in if/else |

### Format Specifiers
Special tokens that begin with `%`, followed by a character that specifies the data type and optional modifiers (width, precision, flags). They control how data is displayed or interpreted.

## 🔗 Related
- [[C Language]]
- [[C user input]]
- [[C Pointer]]
- [[Memory Address in C]]

## References
- W3Schools C Tutorial
