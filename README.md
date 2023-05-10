# CS 3535 ALGORITHMS - Assignment 1: Joy with Parsing

## Introduction

In this assignment, we built a parser capable of identifying whether a computer program is valid and syntactically correct. We used a context-free grammar to define the rules for valid arithmetic expressions and implemented a simple recursive top-down parser to check if a given input string belongs to the corresponding grammar.

## Assignment Description

The assignment involved implementing a recursive top-down parser to parse an input string and check whether it belongs to the corresponding context-free grammar. The grammar used for the assignment was capable of producing all arithmetic expressions using additions, multiplications, and brackets to enforce order of operations.

We followed the recursive top-down parsing algorithm, where we started with the start symbol and tried one of the productions. We went down the tree as long as we replaced non-terminal symbols with their productions, or if we matched the input symbol with terminal symbols in the production string. If at any time the terminal symbol in the production string did not match the input string, or if there were no more rules to apply, we backtracked out of recursion and tried other possibilities.

## Skills Gained

Through this assignment, we gained the following skills:
- Understanding of context-free grammars
- Familiarity with the recursive top-down parsing algorithm
- Ability to implement a recursive top-down parser in Python

## Acknowledgments

This assignment was completed as part of the CS 3535 ALGORITHMS course offered by Appalachian State University. The assignment description was provided by Dr. Raghuveer Mohan who was inspired by Dr Brian C. Dean.
