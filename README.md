Test django + django rest framework project.
See [django REST framework quickstart](http://www.django-rest-framework.org/tutorial/quickstart/).

Clone and do the setup:

```
mkvirtualenv django-test
pip install -r requirements.txt

python manage.py migrate
python manage.py createsuperuser
```

Run an app:

```
python manage.py runserver
```

Open API app: http://localhost:8000 and django admin UI: http://localhost:8000/admin.
