website
=======

Public repo for the MISC informational website.

Introduction
------------

This application is built with Django CMS. Requirements are included in the root repository directory. They can be installed with `pip install -r requirements.txt`.

Installation
------------

You will need the following:

-	`python` and `pip`
-	`virtualenv`

After installing dependencies:

```bash
$ virtualenv env
$ source ./env/bin/activate
$ pip install -r requirements.txt
$ cd miscsite
$ python manage.py migrate
$ python manage.py runserver 0:8000
```

This will run the server on your machine. Anybody as part of your immediate network will be able to access it. You can access it from http://localhost:8000.
