# Django test project

This project is a simple tesqt of Django web framework.
It follows the instructions in a tutorial that can be found [here](https://docs.djangoproject.com/en/1.11/intro/tutorial01/)


### Notepad of useful stuff

* To run the Django development server: 'python manage.py runserver'
* To create a new Django project: 'django-admin startproject mysite'
* To create a new Django app: 'python manage.py startapp polls'
* Localhost default address: <http://127.0.0.1:8000/>
* To make changes in the database model:
..* Change your models (in models.py).
..* Run 'python manage.py makemigrations pools' to create migrations for those changes
..* Run 'python manage.py migrate' to apply those changes to the database.