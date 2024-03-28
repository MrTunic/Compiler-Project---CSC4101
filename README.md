This repository is for a Compiler Project in my CSC 4101 course at LSU.

Project Description:

Write a laxer and a Recursive Descent Parser for the language described by the following specifications:
1- Programs in the language start with the word "program" and end with "end_program"
   Ex. <program> -> program <statements> end_program
2- The language is typeless
3- Statements end with a semicolon
4- The language supports alphanumeric identifier names that do not start with a digit
5- The language supports the operations =, +, -, *, /, %, and ()
6- The language supports if statements (no else) in the form:
   <condition> -> if (<logic expression>) <statements> end_if
7- The language supports binary logical operations in the form
   <logic_expression> -> <var> (==|!=|>|<|>=|=<) <var>
8- The language supports loops that increment a value by 1 until an end value is reached, such that
   <loop> -> loop(<var> = <var> : <var>)<statements> end_loop

   Instructions
• Design the EBNF grammar for the language.
• Write a lexer for the language.
• Write a Recursive Descent Parser for the grammar.
• Add a GUI that allows the user to type in source code for the language and parse programs
written in the language.
• The GUI should produce valid error messages.
• Allowed to use regular expressions for the lexer, but not the parser
