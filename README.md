# DJANGO QUICKSTART
This Repo is about making it easy for you to get a django project up and running.

## Features
- This repo has step-by-step instructions
- It has instructions for setting up `pipenv`
- This repo comes with a *Pipfile*



## Pre-Requisites
>These instruction wouldn't apply to people who are familiar with *Pipenv* && *Django*
>See you at [the check-list](#The-Check-List)
- Python 3.8 
- Pip
- pipenv: ```pip install pipenv```

## Installation

#### `Pipenv` Installation
- `cd` into a desired directory in the terminal
- copy & paste the *Pipfile* I have provided into the directory
>Make sure you're not currently in a virtual environment
`ctrl + d` will exit any active shells
- using the *Pipfile*, create a virtual environment
```shell
pipenv install
```
- Now a *Pipfile.lock* should be created
- Make sure the `pipenv` has the name of your directory by starting the environment

```shell
pipenv shell
```

---

- If your pipenv doesn't have the name of your directory
- Run this command to Remove and Deactivate it.

```shell
pipenv --rm
deactivate
```
- & `ctrl + d` to exit


><i>delete the **Pipfile.lock** file from the directory
>now re-run the **install** command from the correct directory</i>
---

#### `django-admin` project setup
- make sure you are in the `pipenv` by running
```shell
pipenv shell
```
- run this command to create your django project
```shell
django-admin startproject your_project_name
```
- create your first app by running
```python
python manage.py startapp your_app_name
```

*congrats you are all setup!*

---

# The Check List
<input type="checkbox" name="1">
<label for="1"> Create urls.py in app</label><br>