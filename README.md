# cookies

This repo contains a python script to get the cookies set by some http-GET request.

# Set Up Environment

To set up an environment run the following commands in the context of the repo top-level:

```console
user@host:~$ python -m venv venv
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install -r requirements.txt
user@host:~$ deactivate
```

# Get Cookies

To get the cookies from `http://...` run the following commands in a properly set up environment:

```console
user@host:~$ source venv/bin/activate.fish
user@host:~$ python -m pip install --upgrade pip
user@host:~$ python -m pip install --upgrade -r requirements.txt
user@host:~$ python cookies.py http://...
user@host:~$ deactivate
```
