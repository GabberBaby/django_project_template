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

Installation
------------

To setup a local development environment::

    mkvirtualenv newspa
    pip install -r requirements.txt
    ./manage.py syncdb --migrate
    ./manage.py runserver

