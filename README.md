[![HitCount](http://hits.dwyl.io/ro6ley/django-redis.svg)](http://hits.dwyl.io/ro6ley/django-redis)

# Django_Redis

This repository contains the code for this [blogpost](https://stackabuse.com/working-with-redis-in-python-with-django/).

## Running the Application

Clone the repository

``` shell
git clone https://github.com/ro6ley/django-redis.git
```

Check into the cloned repository

``` shell
cd django-redis
```

If you are using Pipenv, setup the virtual environment and start it as follows:

``` shell
pipenv install && pipenv shell
```

Install the requirements

``` shell
pip install -r requirements.txt
```

Configure Redis configuration in `django_redis_demo/settings.py`

Start the Django API

``` shell
python manage.py runserver
```

Send requests to `http://localhost:8000/api/items`
