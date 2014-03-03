{{ project_name }} Project
========================================

About
-----

This project template creates a Django 1.5 project with a base set of applications

Prerequisites
-------------

- Python >= 2.6
- pip
- virtualenv (virtualenvwrapper is recommended)

Usage
-----
Create a Django project:

mkdir {{ project_name }}
cd {{ project_name }}
django-admin.py startproject {{ project_name }} . -e py,rst,example,gitignore --template=https://github.com/GabberBaby/django_project_template/archive/empty_project.zip

Installation
------------

To setup a local development environment::

    mkvirtualenv newspa
    pip install -r requirements.txt
    ./manage.py syncdb --migrate
    ./manage.py runserver

