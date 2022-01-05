# Django Tutorial

## Create Virtual Environment

`python -m venv .tutorial-env`

## Activate Virtual Environment

`.tutorial-env\Scripts\activate`

## Install Dependencies

`python -m pip install -r requirements.txt`

## Migrate database

`python manage.py makemigrations`

`python manage.py migrate`

## Create admin

`python manage.py createsuperuser`

*** Add user name, email and password. ***

## Run Django App

`py manage.py runserver`

### Admin pannel

[/admin/](http://localhost:8000/admin/)

### Poll app

[/polls/](http://localhost:8000/polls/)

## Run Django Test Code
python manage.py test polls
