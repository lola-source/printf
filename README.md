# 0x11. C - printf
***
### _Authors_ Dolores Adagala:[Github](https://github.com/lola-source/printf "github"), Abraham Aguvasu:[Github](https://github.com/AbeNalee/printf "github")
---
|Specifier|Functions|Description|
|---------|--------|-----------|
|s|print_string|prints a string|
|c|print_char|prints a single character|
|i|print_integer|print a number in base 10|
|d|print_integer|print a number in base 10|
|p|print_pointer|print a memory address in base 16 lowercase|
|b|print_binary|prints a number in base 2|
|x|print_hexadecimal_low|print a number in base 16 lowercase|
|X|print_hexadecimal_upp|print a number in base 16 uppercase|
|o|print_octal|print a number in base 8|
|R|print_rot|print a string encoded in rot13 format|
---
### _printf

	A function that produces output according to a format
	Prototype: `int _printf(const char *format, ...);`
---
#### 0 
	 Write a function that produces output
---
#### 1
	Handle the following conversion specifiers
		* d
		* i
---
#### 2
	Create a man page for your function
---
#### 3
	Handle the following custom conversion specifiers
		* b
---
#### 4
	 Handle the following conversion specifiers:
		* u
		* o
		* x
		* X
---
#### 5
	 Use a local buffer of 1024 chars in order to call `write` as little as possible
---
#### 6
	 Handle the following conversion specifier: `p`
---
#### 7
	Handle the following custom conversion specifier:
		* S : prints the string.
		* Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)
---
#### 8
	Handle the following flag characters for non-custom conversion specifiers:
		* +
		* space
		* #
---
#### 9
	Handle the following length modifiers for non-custom conversion specifiers:
		* l
		* h
---
#### 10 
	Handle the field width for non-custom conversion specifiers.
---
#### 11
	Handle the precision for non-custom conversion specifiers
---
#### 12
	Handle the 0 flag character for non-custom conversion specifiers.
---
#### 13
	Handle the - flag character for non-custom conversion specifiers.
---
#### 14
	Handle the following custom conversion specifier:
		* r : prints the reversed string
---
#### 15
	Handle the following custom conversion specifier:
		* R: prints the rot13'ed string
---
#### 16
	All the above options work well together.
