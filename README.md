# algorithms-and-data-structures
Some of the practical work performed in the process of studying the subject "Algorithms and Data Structures".

## 📘 Brackets analyzer
Brackets analyzer is a program that recursively checks the correctness of the bracket sequence specified by the formulas:
```
brackets ::= A | bracket brackets
bracket ::= (B brackets)
```
As a result of the program's execution, for example, when entering an <expression>, the following message will be displayed:
```
<expression> - THIS IS A BRACKETS
-or-
<expression> - THIS IS NOT A BRACKETS
```
The program supports command line and file input and provides instructions for its use.

To compile and run the program, use the following commands:
```
make
./a.out
```
The program supports testing. To run the tests, place the necessary tests in the `Tests/ToCheck` directory, and place the correct answers to these tests in `Tests/Answers`.

To run the tests use `./a.out test`

Directory: `./brackets-analyzer`

## 📂 Hierarchical list depth
The program calculates the maximum depth of a hierarchical list represented as a non-empty bracket sequence. For example, for the sequence "( ( l k ) ( a () e ) )" the maximum depth is 2.

The program supports command line and file input and provides instructions for its use.

To compile and run the program, use the following commands:
```
make
./a.out
```
The program supports testing. To run the tests, place the necessary tests in the `Tests/ToCheck` directory, and place the correct answers to these tests in `Tests/Answers`.

To run the tests use `./a.out test`

Directory: `./hlist-depth`

## 🌳 Infix and postfix expressions using binary tree
This program does the following:
* Construction of a binary tree for a given formula;
* Simplifying a tree by performing subtraction, where the minuend and the subtrahend are numbers, and the result is a number or a formula of the form "(0 - number)";
* Output of infix and postfix records of the received formula or notification of an error in the formula.

Examples:

```
input:
91-21-+

output:
Postfix output - 81+
Infix output - (8+1)
```
```
input:
((((((((((9-1)-(5-9))-1)-2)-1)-1)-(9*1))-(1*2))+2)-5)

output:
Postfix output - 804--1-2-1-1-91*-12*-2+5-
Infix output - (((((((((8-(0-4))-1)-2)-1)-1)-(9*1))-(1*2))+2)-5)
```

The program supports command line and file input and provides instructions for its use.

To compile and run the program, use the following commands:
```
make
./a.out
```

Directory: `./formula-bintree`

## ⚖️ AVL Tree
The program implements the construction of an AVL tree from an initial set of elements (keys) with the implementation of the ability to insert and delete an element into the current tree,
as well as a demonstration of the processes occurring with the AVL tree.

The program supports command line and file input and provides instructions for its use.

To compile and run the program, use the following commands:
```
g++ main.cpp
./a.out
```

Directory: `./avl-tree`
