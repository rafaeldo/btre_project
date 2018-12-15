# BT Real Estate Django Example App

This is an example Django app (with PosgreSQL) for a Real Estate Company.

## Building

You need PostgreSQL installed in your machine.
Create a new Database with the name of `btredb`.
You need a USER in the Database with the name of `postgres` and password `root` (but you can change it in: `btre > settings.py`).

It is best to use the python `virtualenv` tool to build locally.

Mac:

```sh
$ cd btre_project
$ python3 -m venv ./venv
$ source venv/bin/activate
$ python manage.py migrate
$ python manage.py runserver
```

Windows:

```sh
$ cd btre_project
$ python3 -m venv ./venv
$ cd venv/Scripts
$ cd activate.bat
$ python manage.py migrate
$ python manage.py runserver
```

Then visit `http://localhost:8000` to view the app.