
![alt text](./icon.jpg)

# Django Basecamp
장고는 

## Feature
- [X] Create App
- [X] Django DB Migration
- [X] Django Admin
- [ ] Jinja Template


## Convention
 
### Import
장고 프로젝트에서 임포트하는 방식에 대한 가이드는 아래와 같다. 

### Import Sequence
- Standard Library
- Core Django
- Third Party
- Private Project

### Explicit Relative Imports
- Absolute Import: 현재 app 외부에서 사용
- Explicit Relative Import: 현재 app 내부에서 사용


## Getting started

우선 장고 프레임워크를 생성하는 방식은 다음과 같다.

### Prerequisite
- Virtual environment
```buildoutcfg
$ python3 -m venv .venv
```

- Project creation
```buildoutcfg
$ django-admin.py startproject conf .
```

- App creation
```buildoutcfg
$ django-admin.py startapp app(앱이름)
```

- Project structure
```buildoutcfg
.
├── README.md
├── app
│   ├── app
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   └── manage.py
└── conf
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── migrations
    │   └── __init__.py
    ├── models.py
    ├── tests.py
    └── views.py
```

## Links
- [cookiecutter-django](https://github.com/pydanny/cookiecutter-django)
- [django project](https://docs.djangoproject.com/en/2.1/intro/)


