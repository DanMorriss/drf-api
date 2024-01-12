![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

[Django Rest Framework Docs](https://www.django-rest-framework.org/)
[Filtering Docs](https://www.django-rest-framework.org/api-guide/filtering/)
[Django Generics Docs](https://www.django-rest-framework.org/api-guide/generic-views/#attributes/)
[Django Related Name Docs](https://docs.djangoproject.com/en/3.2/ref/models/fields/#django.db.models.ForeignKey.related_name)
[Django Unique Together Docs](https://docs.djangoproject.com/en/3.2/ref/models/options/#unique-together)


`python3 -m venv venv`

`source venv/bin/activate`

`pip3 install 'django<4'`

`django-admin startproject drf_api .`

`pip install django-cloudinary-storage`

`pip install Pillow` - Has image processing capabilities needed for this project.

`python3 manage.py startapp profiles`

`python3 manage.py makemigrations`

`python3 manage.py migrate`

`python3 manage.py createsuperuser`

`python3 manage.py runserver`

`pip3 freeze > requirements.txt`

`pip install djangorestframework`

`python3 manage.py startapp posts`

`python3 manage.py test`

