


Create a virtual environment  for the python installation.
```
python -m venv [config folder name]
```

This will help to control the version and dependencies.

```
pip isntall django
```

```
django-admin
```

```
django-admin startproject [project name]
```

```
django-admin startproject [project name] .
```

```
python manage.py runserver
```

Django-rest-framework

```
pip install djangorestfrmework
```


[Django cors headers](https://youtu.be/38XWpyEK8IY?si=D--mp6W_ArW4ziI-&t=584)

```
pip install django-cors-headers
```

settings.py
```
INSTALLED_APPS = [
	...,
	'corsheaders',
	'rest_framework',
    'tasks'
]
```

```
MIDDLEWARE = [
	...,
	'corsheaders.middleware.CorsMiddleware'
	'django.middleware.common.CommonMiddleware',
	...,
]
```


```
# cors authorization

CORS_ALLOWED_ORIGINS = []
```
