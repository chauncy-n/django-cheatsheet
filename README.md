# django-cheatsheet

## How to create a new Django project
```bash
django-admin startproject projectname
```

## How to start the Django development server
```bash
python3 manage.py runserver
```


## But how do I stop it
```
ctrl + c
```
## How to create a new application in the project
```bash
python3 manage.py startapp main_app
```

## Django directory structure
```
djangoproject
|
| -djangoproject
|  |
|  | -settings.py: Main settings for project (database, apps, config, etc.)
|  | - urls.py: Main URLs for entire project
|
| -application_name
|  |- static: (dir)holds all static file (css, js, aux, forms)
|  |- templates: (dir) Holds all HTML template files
|  |- migrations: This holds all migration files
|  |- admin.py: This is where we register data models
|  |- models.py: This is where we put all models
|  |- views.py: This is where we put the functions that run our routes
|  |- urls.py: Every URL for our site is defined here
|
|- manage.py: lets us change 
```
