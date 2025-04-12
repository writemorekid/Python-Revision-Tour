# 1. Python Revision Tour

## 1.1 Introduction

Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

Key features of Python:
- Easy to learn and use
- Interpreted language
- Dynamically typed
- Extensive standard library
- Community support and third-party modules

## 1.2 Tokens in Python

Tokens are the smallest units in a Python program. The Python interpreter breaks the program into these tokens for interpretation. There are five types of tokens in Python:

1. Keywords  
2. Identifiers  
3. Literals  
4. Operators  
5. Punctuators (also known as delimiters)

### 1.2.1 Keywords

Keywords are reserved words in Python that have special meaning and cannot be used as identifiers (like variable names, function names, etc.).

Some commonly used Python keywords include:
- `if`, `else`, `elif`
- `for`, `while`, `break`, `continue`
- `def`, `return`, `lambda`
- `import`, `from`, `as`
- `class`, `try`, `except`, `finally`
- `True`, `False`, `None`, `and`, `or`, `not`, `is`, `in`

> 💡 Python keywords are case-sensitive and are always written in lowercase (except `True`, `False`, and `None`).

You can get a full list of Python keywords by using the `keyword` module:

```python
import keyword
print(keyword.kwlist)
