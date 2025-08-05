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

## Example

Using 'test.lox':

<img width="671" height="488" alt="Screenshot (486)" src="https://github.com/user-attachments/assets/7ff8fc37-23d0-4fc5-b73c-69886d997efe" />

Output:

<img width="393" height="118" alt="Screenshot (487)" src="https://github.com/user-attachments/assets/fd7178ce-62d2-4625-8b72-48b68ec993b4" />

## References

Based on Crafting Interpreters
