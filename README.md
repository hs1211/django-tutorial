
![alt text](./icon.jpg)

# Django Basecamp
장고는 사용 순서에 대하여 정리하고, 이를 구현한다.

## Import
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

### 사전작업
- 가상환경 설치
```buildoutcfg
$ python3 -m venv .venv
```

- 장고 프로젝트 설치
```buildoutcfg
$ django-admin.py startproject conf .
```

- 장고 앱 생성
```buildoutcfg
$ django-admin.py startapp app(앱이름)
```

- 생성구조
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
### Cookecutter 사용방식
- [cookiecutter-django](https://github.com/pydanny/cookiecutter-django)


## Links
- [django project](https://docs.djangoproject.com/en/2.1/intro/)


