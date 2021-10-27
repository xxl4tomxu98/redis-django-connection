# Django_Redis

This repository contains the code for this [blogpost](https://stackabuse.com/working-with-redis-in-python-with-django/).

## Running the Application

Clone the repository

``` shell
git clone https://github.com/xxl4tomxu98/django-redis-connection.git
```

Check into the cloned repository

``` shell
cd django-redis
```

If you are using Pipenv, setup the virtual environment and start it as follows:

``` shell
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install wheel
pip install -r requirements.txt
python manage.py django_redis_demo/runserver
```

Send requests to `http://localhost:8000/api/items`
