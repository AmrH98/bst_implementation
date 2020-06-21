# bst_implementation

 implement an interpreter that executes instructions and print the result of execution. 
 Therefore, your program should accept a text file as source code, and then you should parse the input 
 file and print the value of each variable
 
 -----------
 First, the output of the process should be the display of all variables each one with its value,
 sorted by the variable name:
 Second, all variables are displayed each one with its value sorted by value; such as:

￼￼￼￼￼￼X = 12.5
Y = X*4/5
Z = X*Y/5
M = Z*-2
K = 10.5+ (Z-2.5)/(X+Y)
￼￼￼K = 11.5 M = -50 X = 12.5 Y = 10 Z = 25

# Requirements
 The following Expression Evaluation should be done by converting it from infix to postfix notation, using stacks.
Variables must be stored in a BST each node having a key/value:
 Key is the variable name
 Value is the value of the variable
Insertion of a new item bust be done by calling a function put(k,v) where k
is key and v is value:
 If the key already exists update the value o If not, insert a new key/value pair.
 Sorting with variable Name will be using in order traversal for BST.
 Sorting with value will be using heap sort Algorithm.
 Data Structures used:
 Arrays
Stacks
 Binary Search Trees o Heaps
