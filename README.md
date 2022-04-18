#!/bin/bash
#"0" - write a function that produces output according to a format
	prototype: int_printf(const char *format, ...):
	Returns: the number of characters printed (excluding the null byte used to end output to strings)
	write output to stdout, the standard output stream
	format is a character string. the format sting is composed of zero or more directives see #"man_3_printf" for more detail. you need to handle the following conversion specifiers:
		c
		s
		%
	you dont have to reproduce the buffer handling of thr C library printf function
#"1" - handle the following conversion specifiers 
		d
		i
#"2" - create a man page for your functions
#"3" - handle the following custom conversion specifiers
		b: the unsigned int argument is converted to binary
#"4" - handle the following conversion specifiers
		u
		o
		x
		X
#"5" - use a local buffer of 1024 chars in order to call write as little as possible
#"6" - handle thr following conversion specifier: p
#"7" - handle the following custom conversion specifier: 
		s: prints the string
#"8" - handle the following flag characters for non_custom conversion specifiers:
		+
		space
		#
#"9" - handle the following length modifiers for non-custom conversion specifiers:
		l
		h
	conversion specifiers to handle : d, i, u, o, x, X
#"10" - handle the field width for non-custom conversion specifiers
#"11" - handle the precision for non-custom conversion specifiers
#"12" - handle the 0 flag character for non custom conversion specifiers
#"13" - handle the - flag character for non-custom conversion specifiers
#"14" - handle the following custom conversion specifiers
		r: prints the reversed stirng
#"15" - handle the following custom conversion specifier
		R: prints the rot13'ed string
#"16" - * all the above options work together 
