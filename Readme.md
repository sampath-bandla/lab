## Django RESTApi Hellow World Project

This is my Lab Project, which is the task of creating a simple API call using Django(Python)

## How to start server
The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/sampath-bandla/lab.git
$ cd lab
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ py -m venv env
$ source env/Scripts/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ python manage.py runserver
```

And now you can access api call using `http://127.0.0.1:8000/hello/`
