# Django Learn Documentation
### 01. Django Envaronment  
Oepn CMD command this line
```
python -m venv env      # python -m envaronment enveronmentName
env\scripts\activate
```
### 02. Django install and create project
Get install django in command this line
```
pip install django
django-admin startproject projectName         # Create Project in command this line
pip install pillow           # for image use this project
```
### 03. Django install Bootstrap
```
pip install django-bootstrap-v5
```
use settings.py
```
INSTALLED_APPS = [
    'bootstrap5',
]
```
use base.html
```
<head>
  <title>{% block title %}{% endblock %}</title>
  {% load bootstrap5 %}
  {% bootstrap_css %}
  {% bootstrap_javascript %}
</head>
```
### 04. Django Create App 
Get in Command line
```
py manage.py startapp appName
```
use settings.py
```
INSTALLED_APPS = [
    'appName',
]
```
### 05. Django Create Super user 
Get in Command line
```
py manage.py makemigrations
py manage.py migration
py manage.py createsuperuser
```

### 06. Django server 
```
# How to Run Server
py manage.py runserver          # https://127.0.0.1:8000/ or https://localhost:8000    
# How to Change Port
py manage.py runserver 8888     # https://127.0.0.1:8888/ or https://localhost:8888  
# How to Stop Server
ctrl+c
```
