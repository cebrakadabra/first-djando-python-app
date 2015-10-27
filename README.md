#A django project
This is a python application realised with the django framework
****************************************************************

##It’ll consist of two parts:

- A public site that lets people view polls and vote in them.
- An admin site that lets you add, change and delete polls.

##Progress doc
- 1. setup django and check if it's running with default setup
- 2. defining models, basically the db layout, install polls app in settings
-- $ python manage.py makemigrations polls (migrate changes)
-- $ python manage.py sqlmigrate polls 0001 (show sql statements)
-- $ python manage.py migrate (rendering model states into db)
- 3. ...
