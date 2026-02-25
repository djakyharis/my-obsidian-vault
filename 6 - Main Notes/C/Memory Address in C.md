
2026-01-31 14:53

Status:

Tags:

# Memory Address
When a variable is created in C, a memory address is assigned to the variable.
The memory address is the location of where the variable is stored on the computer (stored somewhere in RAM).

When we assign a value to the variable, it is stored in this memory address.
To access it, use the reference operator (`&`), and the result represents where the variable is stored:

![[Pasted image 20260131151954.png]]

`&num` is often called a "pointer". A pointer basically stores the memory address of a variable as its value. To print pointer values, we use the `%p` format specifier.


## References
