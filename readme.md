# Beginner's Guide to the Django Rest Framework

This repository is a companion to the pending article on the Django Rest Framework.

step 1: install python 3.5.x or above
#this will also installs pip on your machine

step 2: create virtual environment for your project in current working directory
syntax:   >python -m venv <<name_of_the_virtual_environment>>
command is :  >python -m venv my_first_virtual_env

#here pyhon is tool should be attached to path variable, so that it can be accessible from anywhere
# -m represents create
# venv is the keyword to tell python to create virtual environment for the given name (above example it is my_first_virtual_env)
# above command will create folder with venv name along with Scripts folder inside venv folder and activate file.
# this activate file is used to activate the venv to start work with

step3: activate create virtual environment
syntax: ><<name_of_the_virtual_environment>>\Scripts\activate
example:  >my_first_virtual_env\Script\activate

step4: install django inside virtual env
syntax:  >pip install Django

# this will install django framework inside virtual environment

step5: create Django project
syntax: >django-admin startproject <<project_name>> .
example: >django-admin startproject myfirstproject .

# this will create dJango default project with default files
# dont forget space and dot(.) at the end
# this will create manage.py file as well as a new directory with the name of project.
# one can have multiple projects inside a virtual environment.

step5: running django project
syntax: >python manage.py runserver

# here manage.py is a python file create by django-admin tool while creating the project. 

step6: exit from virtual environemtn
syntax: deactivate

# this command helps you to get exit from the virtual environment. So that you can shift to another virtual environment or to access other tools.
