# 0x0C. Python - Almost a circle

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn about unit testing, serialization, deserialization, JSON, `args`, and `kwargs` in **Python**.

## Apparatus
### Python Scripts
* Used `vi` as editor
* All files are interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All files end with a new line
* The first line of all files is exactly `#!/usr/bin/python3`
* A `README.md` file, at the root of the folder of the project
* Codes use the pycodestyle (version 2.8.*)
* All files are executable
* The length of all files is tested using `wc`
* All modules have the documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All classes have the documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All functions (inside and outside a class) have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)

### Python Unit Tests
* Used `vi` as editor
* All files end with a new line
* All test files are inside the folder `tests`
* used the `unittest module`
* All test files are Python files (extension: `.py`)
* All test files and folders start with `test_`
* File organization in the tests folder is the same as the project: ex: for `models/base.py`, unit tests are in: `tests/test_models/test_base.py`
* All tests are executed using `python3 -m unittest discover tests` command
* Files are also tested file by file by using the `python3 -m unittest tests/test_models/test_base.py` command

## Files

Inside the `models` folder:

| Filename | Description |
| -------- | ----------- |
| `__init__.py` | Script that converts the directory as a package |
| `base.py` | Base class of geometrical instances |
| `rectangle.py` | Class that inherits attributes references from `Base` class |
| `square.py` | Class that inherits attributes references from `Square` class |

Each class contains public/private attributes, class, and static methods. Also, these class raise exceptions when required.

Inside the `tests/test_models` folder:

| Filename | Description |
| -------- | ----------- |
| `__init__.py` | Script that converts the directory as a package |
| `test_base.py` | Module that contains unittests to the `Base` class |
| `test_rectangle.py` | Module that contains unittests to the `Rectangle` class |
| `test_square.py` | Module that contains unittests to the `Square` class |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
