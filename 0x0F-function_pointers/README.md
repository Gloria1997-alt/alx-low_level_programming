i0x0F. C - Function pointers
Write a function that prints a name.

Prototype: void print_name(char *name, void (*f)(char *));

Write a function that executes a function given as a parameter on each element of an array.

Prototype: void array_iterator(int *array, size_t size, void (*action)(int));
where size is the size of the array

and action is a pointer to the function you need to use

The program prints the result of the operation, followed by a new line
You can assume that the result of all operations can be stored in an int
if the number of arguments is wrong, print Error, followed by a new line, and exit with the status 98
if the operator is none of the above, print Error, followed by a new line, and exit with the status 99
if the user tries to divide (/ or %) by 0, print Error, followed by a new line, and exit with the status 100
This task requires that you create four different files.


