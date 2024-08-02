# Django Learn Documentation
### 01. Django Envaronment  
Oepn CMD command this line
```
python -m venv env      # python -m envaronment enveronmentName
```
Get in Envaronment command this line
```
env\scripts\activate
```
### 02. Django install and create project
Get install django in command this line
```
pip install django
```
Create Project in command this line
```
django-admin startproject projectName
```
```
pip install pillow       # for image use this project
```
### 03. Django install Bootstrap
Get in Command line
```
pip install django-bootstrap-v5     # for use Bootstrap 5
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
### 10. Django server 
```
# How to Run Server
py manage.py runserver          # https://127.0.0.1:8000/ or https://localhost:8000    
# How to Change Port
py manage.py runserver 8888     # https://127.0.0.1:8888/ or https://localhost:8888  
# How to Stop Server
ctrl+c
```
### 10. Django server 
```
# How to Run Server
py manage.py runserver          # https://127.0.0.1:8000/ or https://localhost:8000    
# How to Change Port
py manage.py runserver 8888     # https://127.0.0.1:8888/ or https://localhost:8888  
# How to Stop Server
ctrl+c
```
