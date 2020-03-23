# Usefull comands

Run
```
python manage.py runserver
```

New app
```
python manage.py startapp polls
```

Generate migrations
```
python manage.py makemigrations polls
```

Show migrations sql
```
python manage.py sqlmigrate polls 0001
```
Run migrations
```
python manage.py migrate
```
Run db shell
```
python manage.py dbshell
```
Run python shell
```
python manage.py shell
```

Check for problems
```
python manage.py check
```

To test
```
python manage.py shell

from django.test.utils import setup_test_environment
setup_test_environment()

from django.test import Client
client = Client()
response = client.get('/')
```

```
python manage.py test polls
```