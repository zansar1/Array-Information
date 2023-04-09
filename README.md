# Array-Information

This C program initializes an array of integers and prints the array's address, the addresses of each array index, and the size of the array.

The main() function first initializes an array of integers with the values {1,2,3,4,5}. It then prints the address of the entire array using the %p format specifier for pointers.

Next, a do-while loop is used to print the addresses of each index in the array using a pointer to the ith element in the array. The loop condition checks that i is less than 5, the number of elements in the array.

Finally, the program prints the size of the array using the sizeof() operator, which returns the size of the array in bytes.

This program can be used as a starting point for understanding arrays in C, and for exploring how arrays are stored in memory.
