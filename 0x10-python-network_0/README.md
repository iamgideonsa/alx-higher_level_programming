# 0x10. Python - Network #0

This project was done during **ALX SE Studies** at **ALX School**. The end game is to be able to explain to anyone, **without the help of Google**:
* What a URL is
* What HTTP is
* How to read a URL
* The scheme for a HTTP URL
* What a domain name is
* What a sub-domain is
* How to define a port number in a URL
* What a query string is
* What an HTTP request is
* What an HTTP response is
* What HTTP headers are
* What the HTTP message body is
* What an HTTP request method is
* What an HTTP response status code is
* What an HTTP Cookie is
* How to make a request with cURL
* What happens when you type `google.com` in your browser (Application level)

## Tech
* Used editors: `vi`, `vim`, and `emacs`
* A `README.md` file at the root of the folder of the project
* All Scripts are tested on Ubuntu 20.04 LTS
* All Bash scripts are exactly 3 lines long (`wc -l file` should print 3)
* All files end with a new line
* All files are executable
* The first line of all Bash scripts is exactly `#!/bin/bash`
* The second line of all Bash scripts is a comment explaining what the script is doing
* All `curl` commands have the option `-s` (silent mode)
* All files are interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
* The first line of all Python files is exactly #!/usr/bin/python3
* Codes use the pycodestyle (version `2.8.*`)
* All modules are documented: `python3 -c 'print(__import__("my_module").__doc__)'`
* All classes are documented: `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`
* All functions (inside and outside a class) are documented: `python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`
* The documentation length is verified

## Files

| Filename | Description |
| -------- | ----------- |
| `0-body_size.sh` | A Bash script that takes in a URL, sends a request to that URL, and displays the size of the body of the response |
| `1-body.sh` | A Bash script that takes in a URL, sends a `GET` request to the URL, and displays the body of the response |
| `2-delete.sh` | A Bash script that sends a `DELETE` request to the URL passed as the first argument and displays the body of the response |
| `3-methods.sh` | A Bash script that takes in a URL and displays all HTTP methods the server will accept. |
| `4-header.sh` | A Bash script that takes in a URL as an argument, sends a `GET` request to the URL, and displays the body of the response |
| `5-post_params.sh` | A Bash script that takes in a URL, sends a `POST` request to the passed URL, and displays the body of the response |
| `6-peak.py, 6-peak.txt` | A function that finds **a peak** in a list of unsorted integers. |
| `100-status_code.sh` | A Bash script that sends a request to a URL passed as an argument, and displays only the status code of the response. |
| `101-post_json.sh` | A Bash script that sends a JSON `POST` request to a URL passed as the first argument, and displays the body of the response. |
| `102-catch_me.sh` | A Bash script that makes a request to `0.0.0.0:5000/catch_me` that causes the server to respond with a message containing `You got me!`, in the body of the response. |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
