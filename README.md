## Simple SNS

This is a basic CRUD application using Python 3.7 and Django framework.
You can signup and create discussion groups. Users will be able to join/leave groups and post dicussions in these groups.

### Install

If you don't have pipenv installed, please install it through pip.

```
pip install pipenv
```

Use pipenv to install all required packages and start your virtual environment.

```
pipenv shell
pipenv install
```

You first need to complete migration before you can start the application.

```
python manage.py makemigrations accounts
python manage.py makemigrations groups
python manage.py makemigrations posts
python manage.py migrate
```

Now you have setup your database, you are ready to start the server.

```
python manage.py runserver
```
