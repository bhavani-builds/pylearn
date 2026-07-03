# Python Exception Handling - Complete Guide with Assignments

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive repository that teaches **Python Exception Handling** through practical assignments, real-world examples, interview questions, and best practices.

Whether you're a beginner or preparing for coding interviews, this repository will help you understand how Python handles runtime errors and how to write robust, fault-tolerant programs.

---

# Table of Contents

- About
- Learning Objectives
- What is Exception Handling?
- Why Exception Handling is Important
- Topics Covered
- Assignments Included
- Real-World Applications
- Frequently Asked Questions
- Interview Questions
- Common Errors
- Best Practices
- Repository Structure
- Resources
- Author

---

# About

Exception Handling is one of the most important concepts in Python programming. Instead of allowing your application to crash when an error occurs, Python provides mechanisms to detect, handle, and recover from runtime errors.

This repository contains practical assignments that demonstrate how to use exception handling effectively in Python.

---

# Learning Objectives

After completing this repository, you will be able to:

- Understand runtime errors
- Use `try`, `except`, `else`, and `finally`
- Handle multiple exceptions
- Create custom exceptions
- Read files safely
- Handle user input errors
- Debug programs efficiently
- Write reliable Python applications

---

# What is Exception Handling?

Exception Handling is a technique used to manage runtime errors without stopping the execution of a program.

Instead of crashing, the program catches the error, displays a meaningful message, and continues executing whenever possible.

Example:

```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
```

---

# Why is Exception Handling Important?

Without exception handling:

- Programs terminate unexpectedly.
- Users receive confusing error messages.
- Data may be lost.
- Applications become unreliable.

With exception handling:

- Programs become more stable.
- Errors are easier to debug.
- Users receive meaningful messages.
- Resources such as files are closed properly.

---

# Topics Covered

## Basic Exception Handling

- try
- except
- else
- finally

---

## Built-in Exceptions

- ZeroDivisionError
- ValueError
- TypeError
- IndexError
- KeyError
- FileNotFoundError
- JSONDecodeError

---

## Advanced Topics

- Multiple Exceptions
- Nested Exception Handling
- Custom Exceptions
- Raising Exceptions
- File Exception Handling
- Network Exception Handling

---

# Assignments Included

✔ Handling Division by Zero

✔ Reading Files Safely

✔ Handling Multiple Exceptions

✔ User Input Validation

✔ Dictionary Key Errors

✔ Nested Exception Handling

✔ List Index Errors

✔ Network Error Handling

✔ JSON Parsing

✔ Creating Custom Exceptions

✔ Exception Handling in Functions

✔ Exception Handling in Classes

---

# Real-World Applications

Exception handling is widely used in:

- Banking Applications
- E-Commerce Websites
- Hospital Management Systems
- Machine Learning Projects
- Data Analysis
- Web Development
- APIs
- Desktop Applications

---

# Frequently Asked Questions

## What is an Exception?

An exception is a runtime error that interrupts the normal execution of a program.

---

## What is the purpose of try?

The `try` block contains code that may produce an exception.

---

## What does except do?

It catches and handles exceptions raised inside the `try` block.

---

## What is finally?

The `finally` block always executes, regardless of whether an exception occurs.

---

## What is else?

The `else` block executes only if no exception occurs.

---

## Why should we use exception handling?

To prevent applications from crashing and provide meaningful error messages.

---

## What is a custom exception?

A user-defined exception created by inheriting from Python's `Exception` class.

Example:

```python
class NegativeNumberError(Exception):
    pass
```

---

# Common Interview Questions

1. What is exception handling in Python?
2. What is the difference between syntax errors and exceptions?
3. Explain `try`, `except`, `else`, and `finally`.
4. What happens if an exception is not handled?
5. How do you raise your own exception?
6. What are custom exceptions?
7. What is the difference between `raise` and `assert`?
8. What are the most common built-in exceptions?
9. Why should `finally` be used while working with files?
10. Can one `try` block have multiple `except` blocks?

---

# Common Errors

- ZeroDivisionError
- FileNotFoundError
- IndexError
- KeyError
- TypeError
- ValueError
- ImportError
- NameError
- AttributeError

---

# Best Practices

- Catch specific exceptions instead of using a generic `except`.
- Keep `try` blocks small and focused.
- Always close files using `finally` or context managers.
- Avoid suppressing exceptions silently.
- Write meaningful error messages.
- Use custom exceptions for application-specific errors.

---

# Repository Structure

```
Exception-Handling/

│── Exception_Handling_Assignments.ipynb

│── README.md

│── examples/

│── practice/

│── outputs/
```

---

# Resources

- Python Official Documentation
- Real Python
- GeeksforGeeks Python
- W3Schools Python

---

# Author

## Neelapala Naga Durga Bhavani

**B.Tech - Electronics and Communication Engineering**

Passionate about:

- Python Programming
- Artificial Intelligence
- Machine Learning
- Embedded Systems
- VLSI Design

GitHub

https://github.com/bhavani-builds

---

## Support

If this repository helped you learn Python Exception Handling, consider giving it a ⭐ on GitHub.

Contributions, suggestions, and feedback are always welcome!

Happy Coding!
