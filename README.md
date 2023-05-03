# django-init

## Installation

install pipenv using pip
```bash
pip install pipenv
```
Create directory for our project. example: our project name is "supershop"
```bash
mkdir supershop
```
Then go to our project using cd and install django using pipenv.
There will craete virtual environment and two new file like package.json
```bash
pipenv install django
```
Now we need to active virtual environment.
```bash
pipenv shell
```
Then we are ready for create our project. .(dot) means our project will create as a name of supershop without create another folder.
```bash
django-admin startproject supershop .
```
After create our project Now we can create many app under our project. But before create new app we need to activate virtual environment.
```bash
python manage.py startapp app_name
```
Now we are ready for run our server.
```bash
python manage.py runserver
```
For port define.
```bash
python manage.py runserver 8000
```
