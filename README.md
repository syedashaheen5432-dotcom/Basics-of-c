# Basics-of-c
Why were programming languages introduced?
They were introduced to solve problems that humans cannot solve efficiently on their own.
A compiler is a tool that converts your high-level code (like C) into machine code. When you write a program, the compiler checks it for errors, translates it, and produces an executable file.
After that, the program runs on your computer. So, the process is: you write, compile, and then execute!
The C programming starts with the line #include <stdio.h>.
#include <stdio.h> contains a standard library function.
so we include this functions in our program it is necessary to write for beginning of a program, but execution starts from main().
that is int main(){ .
In int main(), int is very important because it is a data type.
It specifies the type of value that the main function returns.
what is a Data type?
A data type defines the type of data a variable can store and how much memory is required for it.
Data types are keywords. they are reserved words used to declare variables and they have a predefined meaning.
when you declare a variable, you must use a data type keyword. keywords in always start with lower case and the keywords in c are:-
int-> stores whole numbers(integers)(ex:-0,1,..),
float-> stores decimal numbers with less precision(ex:-36.4,22.0,2.0.),
double-> stores decimal numbers with more precision(ex:-1235.87,3.1415926535),
character-> stores a single character(ex:-'A'),
declaration of a variable:-
int a = 10;/here a is assigned to 10
int → data type
a → variable name
10 → integer value
;-> is called full stop(statement terminator in c).
Now before discussing about printf(),scanf() we have to know about Format specifier.
A Format specifier is a special symbol used in C to tell the compiler what type of data is being input or output.
Format specifier are used in printf(),scanf(). They always start with %.
int->%d, float->%f,char->%c, double->%lf.
printf-> it is a libary function which is use to dislpay the is used to display the output.it shows output not input.
printf-> print on the screen it belongs to the standard I/O library (stdio.h).
printf("a=%d\n",a);-> a=10 will be displayed on the screen.it will not occupy any storage it is a dummy statement.here (\n means next line).
scanf stands for "scan formatted". It is a standard library function used to read data from the keyboard (standard input) and store it into variables. 
scanf("format_specifier", &variable); -> & (Address-of Operator): Crucial for most types. It provides the memory address of the variable so scanf knows where to save the data.
scanf("%d", &a);// in scanf we dont use any kind of \n,\t or comma(,) .
return 0; ->tells the compiler that the program has executed successfully. it sends 0 back to operating system(int main).
0-> success, non-zero value-> error or abnormal termination.
After (;) the program will end with } 
It will start from main and end at }




