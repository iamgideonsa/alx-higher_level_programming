# 0x0B. Python - Input/Output

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn how to open, read, write, and append files from a script in **Python**.

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
* All test files are text files (extension: `.txt`)
* All tests are executed using the command: `python3 -m doctest ./tests/*`
* All modules have the documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All classes have the documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All functions (inside and outside a class) have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)

## Files

| Filename | Description |
| -------- | ----------- |
| `0-read_file.py` | Function that reads a text file (`UTF8`) and prints it to stdout |
| `1-write_file.py` | Function that writes a string to a text file (`UTF8`) and returns the number of characters written |
| `2-append_write.py` | Function that appends a string at the end of a text file (`UTF8`) and returns the number of characters added |
| `3-to_json_string.py` | Function that returns the JSON representation of an object (String)|
| `4-from_json_string.py` | Function that returns an object (Python data structure) represented by a JSON string |
| `5-save_to_json_file.py` | Function that writes an Object to a text file, using a JSON representation |
| `6-load_from_json_file.py` | Function that creates an Object from a "JSON file" |
| `7-add_item.py` | Script that adds all arguments to a Python list, and then saves them to a file |
| `8-class_to_json.py` | Function that returns the dictionary description with a simple data structure (list, dictionary, string, integer, and boolean) for JSON serialization of an object |
| `9-student.py` | Class `Student` that defines a student by its `first_name`, `last_name`, and `age` |
| `10-student.py` | Class `Student` that defines a student based on `9-student.py` |
| `11-student.py` | Class `Student` that defines a student based on `10-student.py` |
| `12-pascal_triangle.py` | Function `def pascal_triangle(n):` that returns a list of lists of integers representing Pascal's triangle of `n` |
| `100-append_after.py` | Function that inserts a line of text to a file, after each line containing a specific string |
| `101-stats.py` | Script that reads `stdin` line by line and computes metrics |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
