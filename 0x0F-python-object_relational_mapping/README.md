# 0x0F. Python - Object-relational mapping

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn how to connect to a MySQL database from a Python script, what ORM means, and how to map a Python Class to a MySQL table.

## Tech
* Used editors: `vi`, `vim`, and `emacs`
* All files are compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
* All files are executed with `MySQLdb` version `2.0.x`
* All files are executed with `SQLAlchemy` version `1.4.x`
* All files end with a new line
* The first line of all files is exactly `#!/usr/bin/python3`
* A `README.md` file at the root of the folder of the project
* All codes use the pycodestyle (version `2.8.*`)
* All files are executable
* Length of files is tested using `wc`
* All modules have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
* All classes have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
* All functions (inside and outside a class) have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
* The length of documentation is verified
* No `execute` with sqlalchemy

## Files

| Filename | Description |
| -------- | ----------- |
| `0-select_states.py` | Lists all `states` from the database `hbtn_0e_0_usa` |
| `1-filter_states.py` | Lists all `states` with a `name` starting with `N` from the database `hbtn_0e_0_usa` |
| `2-my_filter_states.py` | Takes in an argument and displays all values in the `states` table of `hbtn_0e_0_usa` where `name` matches the argument |
| `3-my_safe_filter_states.py` | Takes in an argument and displays all values in the `states` table of `hbtn_0e_0_usa` where `name` matches the argument without injection |
| `4-cities_by_state.py` | Lists all `cities` from the database `hbtn_0e_4_usa` |
| `5-filter_cities.py` | Takes in the name of a state as an argument and lists all `cities` of that state |
| `model_state.py` | Contains the class definition of a `State` and an instance `Base = declarative_base()` |
| `7-model_state_fetch_all.py` | Lists all `State` objects from the database `hbtn_0e_6_usa` |
| `8-model_state_fetch_first.py` | Prints the first `State` object from the database `hbtn_0e_6_usa` |
| `9-model_state_filter_a.py` | Lists all `State` objects that contain the letter `a` from the database `hbtn_0e_6_usa` |
| `10-model_state_my_get.py` | Prints the `State` object with the `name` passed as argument from the database `hbtn_0e_6_usa` |
| `11-model_state_insert.py` | Adds the `State` object "Louisiana" to the database `hbtn_0e_6_usa` |
| `12-model_state_update_id_2.py` | Script that changes the name of a `State` object from the database `hbtn_0e_6_usa` |
| `13-model_state_delete_a.py` | Script that deletes all `State` objects with the name containing the letter `a` from the database `hbtn_0e_6_usa` |
| `model_city.py` | Contains the class definition of a `City`, which inherits from `Base` |
| `14-model_city_fetch_by_state.py` | Prints all `City` objects from the database `hbtn_0e_14_usa` |
| `relationship_city.py` | Same as `model_city.py` |
| `relationship_state.py` | Contains the class definition of a `State` with a relationship with the class `City` |
| `100-relationship_states_cities.py` | Creates the `State` "California" with the `City` "San Francisco" from the database `hbtn_0e_100_usa` |
| `101-relationship_states_cities_list.py` | Lists all `State` objects and corresponding `City` objects, contained in the database `hbtn_0e_101_usa` |
| `102-relationship_cities_states_list.py` | Lists all `City` objects from the database `hbtn_0e_101_usa` |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
