=============
Django-Emails
=============

CRUD app for collecting email addresses

Quick start
-----------

1. Add "emails_app" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'emails_app',
    ]

2. Include the polls URLconf in your project urls.py like this::

    path('emails/', include('emails_app.urls')),

3. Run ``python manage.py migrate`` to create the emails models.

4. Start the development server and visit http://127.0.0.1:8000/emails/
   to create a email (you'll need create user).