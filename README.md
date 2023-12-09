# cookies

[![UNLICENSE licensed][license-badge]][license-url]

[license-badge]: https://img.shields.io/badge/license-UNLICENSE-blue.svg
[license-url]: ./UNLICENSE

[cookies.py](cookies.py) is a Python script to get the cookies set by some http-GET request.

### Installation

To install cookies, first clone the repo.
Then set up an environment by running the following commands in the context of the repo top-level:

```console
user@host:~$ python -m venv venv
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install -r requirements.txt
user@host:~$ deactivate
```

### Usage

To get the cookies from `http://...` run the following command in a properly set up and activated environment:

```console
user@host:~$ python cookies.py http://...
```

### Upgrade

To upgrade the installation of cookies, just remove `./venv`; then pull and reinstall.
