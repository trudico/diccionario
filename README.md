# Diccionario
[![python](https://img.shields.io/badge/python-3.6-blue.svg "python 3.6")](https://docs.python.org/3/whatsnew/3.6.html)
[![django-version](https://img.shields.io/badge/django-2.0-blue.svg "django 2.0")](https://docs.djangoproject.com/en/1.11/releases/1.11/)

## Features

 - Docker containers:
   - Diccionario_postgres:
     - Database configured to `port 5432`
   - Diccionario_redis:
     - Configured to `port 6379`
   - Diccionario_django:
     - Python 3.6
     - Django 2
     - Postgres already configured
     - Production-ready configuration for Static Files, Database Settings, Gunicorn, etc.
     - Enhancements to Django's static file serving functionality via WhiteNoise.
 - Latest Python 3.6 runtime environment.

## Requirements
This project has the following requirements by default:

```
Django==2.0
gunicorn==19.6.0
psycopg2==2.7.3.2
whitenoise==3.2
```
- - -
