# Django REST API base template
Base template for developing Django REST API apps

## Features
- Docker
- Docker Compose
- Github Actions
- DRF
- DRF Spectacular
- PostgreSQL
- Flake8

## Setup commands
1. `docker compose build`
2. `docker compose up`

## Frequent commands
- Add Django app

`docker compose run --rm app sh -c "python manage.py startapp 'appname'"`

- Make db migrations after updating model

`docker compose run --rm app sh -c "python manage.py makemigrations"`

- Run tests

`docker compose run --rm app sh -c "python manage.py test"`

- Run lint check 

`docker compose run --rm app sh -c "python manage.py flake8"`
