# 0x11. Python - Network #1

This project was done during **ALX SE Studies** at **ALX School**. The end game is to be able to explain to anyone, **without the help of Google**:
* How to fetch internet resources with the Python package `urllib`
* How to decode `urllib` body response
* How to use the Python package `requests` #requestsiswaysimplerthanurllib
* How to make HTTP `GET` request
* How to make HTTP `POST`/`PUT`/etc. request
* How to fetch JSON resources
* How to manipulate data from an external service

## Tech
* Used editors: `vi`, `vim`, and `emacs`
* All files are interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
* All files end with a new line
* The first line of all Python files is exactly #!/usr/bin/python3
* A README.md file at the root of the repo, contains a description of the repository
* A `README.md` file at the root of the folder of the project
* Codes use the pycodestyle (version `2.8.*`)
* All files are executable
* The length of the files is tested using `wc`
* All modules have a documentation: (`python3 -c 'print(__import__("my_module").__doc__)'`)
* Used <a href="/rltoken/ddDVKG3F084DP9byugbABw" title="get" target="_blank">get</a> to access to dictionary value by key (it won’t throw an exception if the key doesn’t exist in the dictionary)
* The documentation length is verified
* Codes are not executed when imported (by using `if __name__ == "__main__":`)

## Files

| Filename | Description |
| -------- | ----------- |
| `0-hbtn_status.py` | A Python script that fetches `https://alx-intranet.hbtn.io/status` |
| `1-hbtn_header.py` | A Python script that takes in a URL, sends a request to the URL, and displays the value of the `X-Request-Id` variable found in the header of the response. |
| `2-post_email.py` | A Python script that takes in a URL and an email, sends a `POST` request to the passed URL with the email as a parameter, and displays the body of the response (decoded in `utf-8`) |
| `3-error_code.py` | A Python script that takes in a URL, sends a request to the URL and displays the body of the response (decoded in `utf-8`). |
| `4-hbtn_status.py` | A Python script that fetches `https://alx-intranet.hbtn.io/status` |
| `5-hbtn_header.py` | A Python script that takes in a URL, sends a request to the URL and displays the value of the variable `X-Request-Id` in the response header |
| `6-post_email.py` | A Python script that takes in a URL and an email address, sends a `POST` request to the passed URL with the email as a parameter, and finally displays the body of the response. |
| `7-error_code.py` | A Python script that takes in a URL, sends a request to the URL and displays the body of the response. |
| `8-json_api.py` | A Python script that takes in a letter and sends a `POST` request to `http://0.0.0.0:5000/search_user` with the letter as a parameter. |
| `10-my_github.py` | Python script that takes your GitHub credentials (username and password) and uses the <a href="/rltoken/LjPfW9hW_55YwijGVofyTQ" title="GitHub API" target="_blank">GitHub API</a> to display your `id`. |
| `100-github_commits.py` | A Python script that takes 2 arguments in order to solve this challenge. |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
