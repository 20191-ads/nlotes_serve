# nlotes_serve
Template para proyectos de DTI 2018

## Features

- Python 3.7 runtime environment. 

Install requirements::

    $ pip install pipenv

Install dependencies with pipenv::

    $ pipenv install
    $ pipenv shell

Runing::

    $ (nlotes_serve-u3riQcTX) D:\dev\dti-a\nlotes_serve>manage.py runserver 80

## Demo : https://nlotesserve.herokuapp.com/accounts/login/

	user: admin
	pass: 123

## NOTA
	
	Debe de entrar como administrador para cambiar el accesp del nuevo usuario a is_staff para True
	

## environment content

	(nlotes_serve-E_Ak_RhD) D:\dev\dti2018pro\nlotes_serve>pipenv run pip freeze
	Loading .env environment variables…
	certifi==2019.3.9
	chardet==3.0.4
	defusedxml==0.5.0
	dj-database-url==0.5.0
	Django==2.2
	django-allauth==0.39.1
	django-cors-headers==2.5.2
	django-crispy-forms==1.7.2
	django-debug-toolbar==1.11
	django-filter==2.1.0
	django-heroku==0.3.1
	djangorestframework==3.9.2
	docutils==0.14
	drf-extensions==0.4.0
	gunicorn==19.9.0
	idna==2.8
	oauthlib==3.0.1
	Pillow==6.0.0
	psycopg2==2.8.1
	psycopg2-binary==2.8.1
	python3-openid==3.1.0
	pytz==2018.9
	requests==2.21.0
	requests-oauthlib==1.2.0
	sqlparse==0.3.0
	urllib3==1.24.1
	whitenoise==4.1.2
