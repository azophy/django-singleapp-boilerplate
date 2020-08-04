SINGLE APP DJANGO BOILERPLATE
=============================

Adapted from article by Marios Zindilis ()https://zindilis.com/blog/2017/01/06/django-anatomy-for-single-app.html

## Features
- single app projects structure
- custom User class
- .env file support
- heroku deploy ready

## How To Use

1. Download zip and extract
2. Edit & save example.env as .env . The most important thing to set is the SECRET_KEY variable. Everything else is optional
3. `pip install -r requirements.txt`
4. `python manage.py migrate`
5. `python manage.py runserver`

## How to deploy to heroku
1. Make sure the remote source has been pointing to heroku.
2. Set the apropriate environment variables. At minimum set value for SECRET_KEY using `heroku config:set SECRET_KEY=$(python3 -c 'import secrets;print(secrets.token_urlsafe(50))')`
3. `git push heroku master`


