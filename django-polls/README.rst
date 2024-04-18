INSTALLED_APPS = [
"polls"
]
path("polls/",include ("polls.urls"))
``python manage.py migrate``