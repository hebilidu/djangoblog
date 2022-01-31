SOURCE = YouTube.com
AUTHOR = Corey Schafer
TITLE  = Python Django Tutorial: Full-Featured Web App (blog)
CODE SOURCE = https://github.com/CoreyMSchafer/code_snippets/tree/master/Django_Blog

220126 
Re-create venv using Python 3.10.1 (after installing it on Mac OS X):
[lidu]github> python3 -m venv djangoblog_venv
Activate the venv:
[lidu]github> . djangoblog_venv/bin/activate
Check installed packages:
[lidu]github> pip list
Install Django package:
[lidu]github> pip install django
Check Django version (4.0.1):
[lidu]github> django-admin --version

Using existing project (djangoblog) and application (blog):
[lidu]github> cd djangoblog
Launch server:
[lidu]djangoblog> python manage.py runserver

ORM: Object Relation Mapper

220129 - Part 8 - Add Login, Logout, Profile
Add Pillow Package

220130 Add signal to create profile at user creation

220131 Update User Profile
-- In template's form, do not forget "enctype" encoding type to pass on image data
