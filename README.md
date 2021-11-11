[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

Modern C++ Notebooks by Adam Gatt is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

&nbsp;

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/adamagatt/modern_cpp_notebooks/HEAD)

[These notebooks can be executed on Binder.](https://mybinder.org/v2/gh/adamagatt/modern_cpp_notebooks/HEAD) Click the link to host them in an interactive environment that runs right in your browser!

&nbsp;

# Modern C++ Notebooks

These are a series of Jupyter notebooks intended for bringing long-time C++ developers quickly up to speed with important developments from C++11/14.

These notebooks present content alongside code snippets that can be executed and modified to allow for rapid interactive learning. They are backed by the [xeus-cling](https://github.com/jupyter-xeus/xeus-cling) C++ interpreter.

The material aims to provide high value as quickly as possible by beginning with "easy win" keywords that can be dropped into your code to provide immediate benefit with little thought. Code examples demonstrate the usefulness of these topics, aiming to "show rather than tell".

Later notebooks provide long-form introductions to new concepts, beginning with the problems they solve and discussing design choices and performance considerations that may apply.

This content is aimed towards those who learned C++ to the C++98/03 standard or who code in a "C with Classes" style. The content also includes some pre-modern keywords and accepted best practice, including `explicit`, const references and RAII.

## Content
### 1. Overview
### 2. Easiest Wins
* override
* nullptr
* constexpr
* using
### 3. Other Easy Wins
* explicit
* scoped enumerations
* cast expressions
### 4. Improvements, with Consideration
* const references
* uniform initialisation syntax
* auto
### 5. Lambdas and Closures
### 6. RAII (Stack-Based Resource Management)
### 7. Smart Pointers - `unique_ptr`
### 8. Smart Pointers - `shared_ptr`