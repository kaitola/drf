# Django RESR Framework

## install development environment
### 1. create virtual environment
* python3.7 -m venv /path/to/your/{virtual-env}
### 2. enable your python virtual environment
* source /path/to/your/{virtual-env}/bin/activate
### 3. install django and django-rest-framework
* pip install django
* pip install djangorestframework
### 4. start your first django project
* django-admin startproject {your-project-name}
### 5. create first django app
* python manage.py startup {your-app-name}
### 6. add new app into settings.py file
* "INSTALLED_APPS" array add {your-app-name}
### 7. create templates folder in your app's folder
* cd {your-app-name}
* mkdir templates
## create django MVT file related
### 1. create template file in templates folder
* touch index.html
* create variable named data and express {{data}} (Django template language)
### 2. write views render function in views.py file
* write your render code
### 3. Config URLconf file
* add your route in urlpatterns and import views
