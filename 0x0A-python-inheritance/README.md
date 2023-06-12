# 0x0A. Python - Inheritance

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn about inheritance, superclass, base class, and subclass in **Python**.

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

### Python Test Cases
* Used `vi` as editor
* All files end with a new line
* All test files are inside the folder `tests`
* All tests are executed using the command: `python3 -m doctest ./tests/*`
* All modules have the documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All classes have the documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All your functions (inside and outside a class) should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)

## Files
| Filename | Description |
| -------- | ----------- |
| `0-lookup.py` | Function that returns the list of available attributes and methods of an object |
| `1-my_list.py` | Class `MyList` that inherits from `list` |
| `2-is_same_class.py` | Function that returns `True` if the object is exactly an instance of the specified class; otherwise `False` |
| `3-is_kind_of_class.py` | Function that returns `True` if the object is an instance of, or if the object is an instance of a class that is inherited from the specified class |
| `4-inherits_from.py` | Function that returns `True` if the object is an instance of a class that is inherited from the specified class |
| `5-base_geometry.py` | Empty class `BaseGeometry` |
| `6-base_geometry.py` | Class `BaseGeometry` with public instance method `def area(self):` |
| `7-base_geometry.py` | Class `BaseGeometry` with public instance method that verifies if the input arg is an integer |
| `8-rectangle.py` | Class `Rectangle` that inherits from `BaseGeometry` |
| `9-rectangle.py` | Class `Rectangle` that inherits from `BaseGeometry`, with the `area()` method implemented |
| `10-square.py` | Class `Square` that inherits from `Rectangle` |
| `11-square.py` | Class `Square` that inherits from `Rectangle`, with `str()` method |
| `100-my_int.py` | Class `MyInt` that inherits from `int`. Its `==` and `!=` operators are inverted |
| `101-add_attribute.py` | Function that adds a new attribute to an object if it's possible |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
