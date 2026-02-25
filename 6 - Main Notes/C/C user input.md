
2026-01-31 14:30

Status: #seed 

Tags: 

# User input

### scanf() Function

![[Pasted image 20260131143743.png]]

The `scanf()` function takes two arguments: the format specifier of the variable (`%d` in the example above) and the reference operator (`&myNum`), which stores the memory address of the variable.

![[Pasted image 20260131145027.png]]

When working with strings in `scanf()`, you must specify the size of the string/array (we used a very high number, 30 in our example, but at least then we are certain it will store enough characters for the first name), and you don't have to use the reference operator (`&`).

![[Pasted image 20260131145151.png]]

**Use the `scanf()` function to get a single word as input, and use `fgets()` for multiple words.**





## References
