# Django #

### External cheatsheets to review

https://dev.to/ericchapman/my-beloved-django-cheat-sheet-2056

https://www.codewithharry.com/blogpost/django-cheatsheet/

### Resourse for Class Based Views

(http://ccbv.co.uk/)

---

## Setup project ##

`django-admin startproject <name>`

## Run server ##

`python manage.py runserver`

## Templates ##

[django Documentation](https://docs.djangoproject.com/en/4.0/topics/templates/)

### Tags ###

`{{ variable }}`

### Variables ###

`{% logic %}`

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


