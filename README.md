#A django project
This is a python application realised with the django framework
****************************************************************

##It’ll consist of two parts:

- A public site that lets people view polls and vote in them.
- An admin site that lets you add, change and delete polls.

##Progress doc
- 1. setup django and check if it's running with default setup
- 2. defining models, basically the db layout, install polls app in settings
  - $ python manage.py makemigrations polls (migrate changes)
  - $ python manage.py sqlmigrate polls 0001 (show sql statements)
  - $ python manage.py migrate (rendering model states into db)
- 3. setting up the admin section
- 4. dealing with views and namespaces
- 5. usage of generic views
- 6. testing a model --> python manage.py test polls
- 7. add integration tests for questions
- 8. add static files and use them in the view
- 9. figured out, what should be not in git from django
