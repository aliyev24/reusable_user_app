=====
Custom User
=====

Users is a Django app to use custom user model for projects.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "users" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'users',
    ]


2. Update settings.py:

AUTH_USER_MODEL = 'users.User'

3. Add users app before first migration

4. Run ``python manage.py makemigrations`` and ``python manage.py migrate`` to create the user model.
