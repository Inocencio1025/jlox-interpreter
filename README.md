# jlox-interpreter

A tree-walk interpreter for the Lox programming language, written in Java. Follows the implementation from the book *Crafting Interpreters* by Bob Nystrom.

> I built this as a learning project after discovering the book while preparing for a Programming Languages course. It was a great way to explore interpreters, language design, and core language theory in practice.

## Features

- Scanner (lexer), parser, and interpreter
- Supports expressions, variables, control flow, functions, and classes
- Implements closures, scope resolution, and native functions

## How to Run

Requires Java 11+.

```bash
javac com/craftinginterpreters/lox/*.java
java com.craftinginterpreters.lox.Lox
```

## References

Based on Crafting Interpreters
