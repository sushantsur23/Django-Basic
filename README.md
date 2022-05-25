## Basic Django Project

```
django-admin startproject first_project
```

```
settings.py to store all the project settings
urls.py python script will store all the URL patterns of our project. holds different pages of web application.
wsgi.py acts as web server gateway interface 
manage.py willbe associated with many commands as we build a web application
```
```
cd first_project/
python manage.py runserver
python manage.py startapp first_app
```

```
admin.py register our models can be used with Django interface.
apps.py can place for any application specific configurations
models.py store application data models
test.py series of functions to test our application
views.py functions of requests that can handle request and return response 
migrations folder Directory stores database specific information as it related to the models
```

```
Create function in view - link to urls -- update settings.py
template tagging to inject images into html files
Creating models in django
```
## Part 2 commands
```python
python manage.py migrate  
python manage.py makemigrations first_app
python manage.py shell
python manage.py createsuperuser
pip install Faker
```
# Part 2
```
create models in models.py, register changes to the application
```

# Part 3
```
Use User forms to create a complete website
```
