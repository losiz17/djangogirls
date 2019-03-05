# Thanks

DjangoTutorial: https://djangogirlsjapan.gitbook.io/workshop_tutorialjp
DjangoGirls: https://djangogirls.org/tokyo/

# Set up for Django

We will make a virtualenv called myvenv.

Start your virtual environment by running.

```
$python3 -m venv myvenv
$source myvenv/bin/activate
```


Now that you have your virtualenv started, you can install Django.

```
(myvenv) ~$ python -m pip install --upgrade pip
(myvenv) ~$ pip install django==1.11
```


# Usage

```
(myvenv) ~/djangogirls$ python manage.py runserver
```

