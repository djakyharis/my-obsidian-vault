
2026-01-13 15:19

# Starting with C

*note*: I made this note because I can't code and trying to get better at this thing, so I can actually call myself a CE student starting with C.

here's my roadmap in a nutshell:
1. learn low level (C)
2. learn assembly
3. reverse engineering (bug hunting etc.)
4. learn to code board (esp32 etc.)

<stdio.h> = library input output, preprocessor directive intinya untuk input output

int = integer 

return 0; = main function expected to return integer (jadi kalau 0 itu main functionnya berjalan dengan baik, sebaliknya kalau bukan 0)

printf("text"); = print "text"

// = comment kalau ada ** di tengah bisa jadi multi-line comment


#### Variables
variable = reusable container for a value.
	   Behaves like the value it contains.

int = whole numbers (1,2,3,4,etc.) (4 bytes in modern systems), ex: printf("My number is %d", num);
float = single-precision decimal number (4 bytes), ex: printf("The temperature is %1.f", temp);
double = double-precision decimal number (8 bytes), ex: printf("The value of pi is %.15lf", pi);
char = single character (1 byte), ex: printf("My grade is %c", grade); 
char[] = array of characters (size varies), ex: printf("My name is %s", name);
bool = true or false (1 byte, requires <stdbool.h>), ex: usually use if else case (if bool(isOnline) else...)

#### Format specifier
Format specifier = Special tokens that begin with a % symbol,
		   followed by a character that specifies the data type
		   and optional modifier (width, precision, flags).
		   They control how data is displayed or interpreted.




## References
