# 0x07. Python - Test-driven development

## Learning Objectives

At the end of this project, you should be able to explain the following concepts:

- Why Python programming is awesome
- What's an interactive test
- Importance of tests in software development
- How to write Docstrings to create tests
- How to write documentation for each module and function
- Basic option flags to create tests
- Finding edge cases

## Requirements

### Python Scripts

- Editors: vi, vim, emacs
- Interpreted/compiled on Ubuntu 20.04 LTS using Python 3.8.5
- All files end with a newline character
- The first line of all script files should be exactly `#!/usr/bin/python3`
- Mandatory `README.md` file at the root of the project folder
- Code should use pycodestyle (version 2.8.*)
- All files must be executable
- File length will be tested using `wc`

### Python Test Cases

- Editors: vi, vim, emacs
- All files end with a newline character
- All test files should be inside a folder `tests`
- All test files should be text files (extension: `.txt`)
- All tests should be executed by using this command: `python3 -m doctest ./tests/*`
- All modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All functions should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`)
- Documentation should be a real sentence explaining the purpose of the module, class, or method (length will be verified)

We strongly encourage collaboration on test cases to ensure coverage of edge cases.

