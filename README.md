📘 Project 8 – Pointers (Indicators) in C Language
📌 Overview

This project demonstrates the use of pointers (indicators) in C language through two practical programs:
Folder File Link : https://onlinegdb.com/KY5ZhxYTB

String Length Finder using Pointer
Cube of Array Elements using Pointer

The project helps in understanding how pointers can be used to traverse memory and perform operations efficiently.

🎯 Objectives
Understand the concept of pointers in C
Learn how to manipulate strings using pointers
Perform array operations using pointer arithmetic
Improve logic building using memory addressing
🧩 Program 1: String Length Using Pointer
Online GDB Link 1 : https://onlinegdb.com/ZrJTcJMTK
🔹 Description

This program takes a string input from the user and calculates its length using a pointer instead of built-in functions like strlen().

🔹 Logic
Take input string
Assign pointer to the string
Traverse until '\0'
Count characters
🔹 Code Concept
ptr = str;

while (*ptr != '\0') {
    length++;
    ptr++;
}
🔹 Output Example
Enter any string:
Hello World
Length of the string = 11
🧩 Program 2: Cube of Array Elements Using Pointer
Online GDB Link 2 : https://onlinegdb.com/Wdo5x6-dqI
🔹 Description

This program takes a 2D array input and prints the cube of each element using pointer arithmetic.

🔹 Logic
Accept array size (row x row)
Store elements in 2D array
Pass base address to function
Traverse using pointer and calculate cube
🔹 Code Concept
printf("%d\n", (*ptr) * (*ptr) * (*ptr));
ptr++;
🔹 Output Example
Enter array size:
2

Enter array element [0][0]: 2
Enter array element [0][1]: 3
Enter array element [1][0]: 4
Enter array element [1][1]: 5

Cube of the element:
8
27
64
125
⚠️ Important Notes
The program uses pointer arithmetic to traverse arrays.

In Program 2, the function prints elements twice due to two loops:

for (int i = 0; i < row; i++)

(This can be optimized if needed.)

Use of scanf("%[^\n]", str) allows input with spaces.
🚀 Features
Beginner-friendly pointer implementation
Covers both string and array operations
Helps understand memory traversal
🛠️ Technologies Used
C Programming Language
Standard Libraries: stdio.h, string.h
📚 Learning Outcome

After completing this project, you will be able to:

Use pointers effectively
Traverse strings and arrays using memory addresses
Replace built-in functions with manual logic
👨‍💻 Author

Tirth Salot
