# django-app-gtfs

![Django](https://img.shields.io/badge/Django-5.2-blue)

App de Django para gestión de modelos y utilidades de GTFS para uso en Databús e Infobús

```python
# settings.py
INSTALLED_APPS = [
    ...
    'gtfs',
]
```

> [!IMPORTANT]
> La app utiliza [llaves primarias compuestas](https://docs.djangoproject.com/en/5.2/topics/composite-primary-key/) en los modelos, disponibles desde Django 5.2.
