# Python Revision Tour

## 1.1 Introduction

Python is a high-level, interpreted programming language. It emphasizes readability and simplicity, making it an ideal choice for beginners and experts alike.

## 1.2 Tokens in Python

Tokens are the smallest units of a program, representing the syntax of the language. In Python, tokens are categorized into the following types:

### 1.2.1 Keywords

Keywords are reserved words in Python that have special meaning and cannot be used as identifiers (like variable names). Examples of keywords:
- `if`, `else`, `elif`
- `for`, `while`, `break`, `continue`
- `def`, `return`, `lambda`
- `class`, `try`, `except`, `finally`

### 1.2.2 Identifiers (Names)

Identifiers are names given to variables, functions, classes, modules, and other objects. They must follow these rules:
- Begin with a letter (a-z, A-Z) or an underscore (_)
- The rest of the name can include letters, digits (0-9), and underscores
- Python is case-sensitive, so `Variable` and `variable` are different.

### 1.2.3 Literals (Values)

Literals represent fixed values in Python. There are several types:
- **Integer literals**: Whole numbers, e.g., `5`, `100`
- **Floating-point literals**: Decimal numbers, e.g., `3.14`, `-0.001`
- **String literals**: Enclosed in single or double quotes, e.g., `'Hello'`, `"World"`
- **Boolean literals**: `True`, `False`
- **None**: Represents the absence of a value

### 1.2.4 Operators

Operators perform operations on variables and values. Python includes:
- **Arithmetic operators**: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- **Relational operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical operators**: `and`, `or`, `not`
- **Assignment operators**: `=`, `+=`, `-=`, `*=`, `/=`
- **Bitwise operators**: `&`, `|`, `^`, `~`, `<<`, `>>`
  
### 1.2.5 Punctuators

Punctuators are symbols used in Python syntax, such as:
- Parentheses: `()`
- Square brackets: `[]`
- Curly braces: `{}`
- Comma: `,`
- Colon: `:`
- Period: `.`

## 1.3 Barebones of a Python Program

A basic Python program consists of a series of statements, typically starting with an import statement followed by function definitions and executable code.

```python
# This is a simple Python program
print("Hello, World!")
