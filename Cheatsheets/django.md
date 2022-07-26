# Django #

## Setup project ##

`django-admin startproject <name>`

## Run server ##

`python manage.py runserver`

## Templates ##

### main.html ###

```
{% include 'navbar.html' %}

{% block content %}

{% endblock %}
```

### page.html ###

```
{% extends 'main.html' %}

{% block content %}

<h1>Home Template</h1>

{% endblock %}
```
