```
$ git clone https://github.com/jrajmundtest/my-first-blog.git
$ cd my-first-blog
$ python3 -m venv venv
$ source venv/bin/activate
(venv)$ pip install -U pip
(venv)$ pip install wheel eggs
(venv)$ pip install -r requirements

(venv)$ python manage.py makemigrations
(venv)$ python manage.py migrate
(venv)$ python manage.py createsuperuser

(venv)$ python manage.py runserver
```