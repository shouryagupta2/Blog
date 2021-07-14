# Django Blog


Features 
=
- User Registration
- User Login & Logout
- User Profile
- Create, Update, Edit & Delete Posts
- Comments
- Search
- Customized admin panel

How To Use
=
## Clone project & Install Requirements
> Make sure you have already installed python3 and git.
```
$ git clone https://github.com/pubuser7/django-blog.git && cd django-blog
$ pip install -r requirements.txt
```
## Migrate & Collect Static
```
$ cd src && python manage.py migrate
$ python manage.py collectstatic
```
## Create Admin User
```
$ python manage.py createsuperuser
```
## Run Server
```
$ python manage.py runserver
```

