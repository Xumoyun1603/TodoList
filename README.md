## This is my todo website:

http://khumoyuntodos.herokuapp.com/

## How to start

Clone repository and install requirements in your virtual environment

```
pip install -r requirements.txt
```

and make migrations

```
python manage.py makemigrations
python manage.py migrate
```

To adding content you should create a categories but before that, create a superuser

```
python manage.py createsuperuser
```

Then start the site

```
python manage.py runserver
```
