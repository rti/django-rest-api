# django-rest-api

An opinionated project template for creating REST APIs

## Based on

 - Django https://www.djangoproject.com/
 - Django REST framework https://www.django-rest-framework.org/
 - Django CORS Headers https://pypi.org/project/django-cors-headers/
 - Token Auth https://www.django-rest-framework.org/api-guide/authentication/#tokenauthentication
 - Postgres https://www.postgresql.org/
 - Docker https://www.docker.com/
 - Docker Compose https://docs.docker.com/compose/

## How to use

Install docker-compose

### Start the API

```shell
docker-compose up
```

Direct your browser to http://localhost:8000

### Run tests

```shell
docker-compose run --rm django python manage.py test --noinput --failfast
```
