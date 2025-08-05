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
<img width="672" height="490" alt="Screenshot (485)" src="https://github.com/user-attachments/assets/4a9150d0-a562-47f3-b7d3-bc3736eff618" />

Output:
<img width="560" height="72" alt="Screenshot (484)" src="https://github.com/user-attachments/assets/de5f94a5-fe19-4c47-b185-dff4ab63db15" />

## References

Based on Crafting Interpreters
