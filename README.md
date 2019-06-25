# Django REST Framework Example

An example API build using Django REST Framework

## Requirements:

  - docker
  - docker compose

## Run with:

    $ docker-compose up

Note: Run migrations and create superusers inside the running container.

	$ docker-compose run api /app/api/manage.py migrate
    $ docker-compose run api /app/api/manage.py createsuperuser
