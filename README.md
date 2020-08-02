# DjangoForum

## QUICK START
```bash
# run django server
cd ~ && cd DjangoForum/forumapp 
python manage.py runserver

# migrate DB
cd ~ && cd DjangoForum/forumapp 
python manage.py migrate
python manage.py makemigrations polls

# run test 
cd ~ && cd DjangoForum/forumapp 
python manage.py test polls
```

### Help commands
```bash
# find Django source files
python -c "import django; print(django.__path__)"
```

### Ref
- official doc
	- https://docs.djangoproject.com/en/3.0/
- testing django
	- https://docs.djangoproject.com/en/3.0/topics/testing/
- doc
	- https://github.com/yennanliu/DjangoForum/tree/master/doc
- Forum
	- https://twaigroup.com/community/
	- https://www.reddit.com/r/django/comments/2cr755/best_django_forum_application/
	- https://djangopackages.org/grids/g/forum/
