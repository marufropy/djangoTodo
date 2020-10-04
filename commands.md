### Commands Gist
# Django Commands

```bash
# Install pipenv

pip install pipenv
```

```bash
# Create Venv

pipenv shell
```

```bash
# Install Django

pipenv install django
```

```bash
# Check Django Version

python -m django --version
```

```bash
# Create project

django-admin startproject name
cd name
```

```bash
# Run server on http: 127.0.0.1:8000 (ctrl+c to stop)

python manage.py runserver
```

```bash
# Run initial migrations

python manage.py migrate
```

```bash
# Create admin user

python manage.py createsuperuser
```

```bash
# Create app

python manage.py startapp name
```

```bash
# Create migrations

python manage.py makemigrations name
```

```bash
# Run migrations

python manage.py migrate
```

```bash
# Using the shell

python manage.py shell
>>>  quit()
```