# Email as username for Django authentication

IMPORTANT: This has to be done before you deploy your project, preferably right at the beginning

https://www.fomfus.com/articles/how-to-use-email-as-username-for-django-authentication-removing-the-username

### Requirements ####
- Python 3.5
- Django 2.1.7
- psycopg2-binary 2.7.7

### Instalation ####
1. Copy mailauth app into your project
2. Add and AUTH_USER_MODEL and  add this app to your INSTALLED_APPS Django setting.
3. ./manage.py makemigrations
4. ./manage.py migrate
