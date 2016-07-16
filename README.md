# django_blog

a blog written in python django. users can comment, can send email. for learning purposes only. 
Install
=======
``` bash
virtualenv project
cd project
pip install django
django-admin.exe startproject mysite
cd mysite
```
edit settings.py, add blog in INSTALLED_APPS then:
``` bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
go to http://localhost/blog/

