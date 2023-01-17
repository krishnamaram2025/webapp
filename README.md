# Title
Django application to perform CRUD operations

# Technologies used
Frontend:  HTML

Backend: Django

Database: SQL


# Pre-Requisites
$pip install Django

$django-admin startproject webapp

$python manage.py startapp employee


## Execution Flow
* Clone the project:
```
$ git clone https://github.com/FahadulShadhin/crudapp.git
```

* Install required packages:
```
$ pip install -r requirements.txt
```

* Make migrations to database:
```
$ python manage.py makemigrations
$ python manage.py migrate
```
* Get admin access:
```
$ python manage.py createsuperuser (enter username, email, password)
```

* Run server:
```
$ python manage.py runserver
```

* Testing
http://127.0.0.1:8000
http://127.0.0.1:8000/admin


