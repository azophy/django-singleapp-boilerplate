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
4. `python manage.py runserver`
5. To deploy to heroku, first make sure the remote source has been pointing to heroku. then just `git push heroku master`


