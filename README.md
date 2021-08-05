# Source Code for Black Hat Python in Python3
Source code for the book "Black Hat Python" by Justin Seitz. The code has been fully converted to Python 3, reformatted to comply with PEP8 standards and attempts have been made to eliminate dependency issues involving the implementation of deprecated libraries.

## Usage
Simply choose a directory (DIR) in which to clone the project using
`git clone`, create a new virtual environment or `venv` for it (recommended
) and install the requirements using `pip install`.

```
user@host:~/DIR$ https://github.com/M108Falcon/Black-Hat-py3.git
user@host:~/DIR$ python3 -m venv env
user@host:~/DIR$ source env/bin/activate
(env) user@host:~/DIR$ pip install -r requirements.txt
```

If using github cli:
```
user@host:~/DIR$ gh repo clone M108Falcon/Black-Hat-py3
```
Rest of the steps are same as of git method

## Notes
- The book was made available in its entirety by Internet Archive, right
 [here](https://archive.org/details/pdfy-rJnW-pPgiHK61dok/).
- Minor bugs that generated warnings by the interpreter have been fixed
 throughout the code without altering its characteristics.
- Additional files/dependencies that were required to make the code work were added to their respective chapters.
