# Compiler
Chez Scheme Compiler

A full compiler for Chez Scheme built in Chez Scheme using Inline Assembly of Intel X86 architecture for 64-bit. 

Combining all compilation pipeline steps (Lexical Analysis, Parsing, Tagging, AST generation, Code Generation) using automata, taking an original scheme expression, processing it into tokens, then S-expressions and so (by compilation pipeline) until the final Assembly language code is generated and then it operates the requested code commands on the computer.
