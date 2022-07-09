# django-mongodb
Django-MongoDB

## Prerequisites

```
Python 3.5>
Poetry
Docker && docker-compose

```

## Quickstart

1. Clone this project

2. Install dependencies:

   ```shell
   cd django_project
   python3 -m venv .venv
   source .venv/bin/activate 
   pip install -r requirements
   ```
   
2. Run docker dev server environment:

   ```shell
   docker-compose up -d --build 
   docker-compose exec web python manage.py migrate
   ```
