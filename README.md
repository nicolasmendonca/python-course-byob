# Vagrant

## Starting

```bash
$ vagrant up
```

## Stopping

```bash
$ vagrant halt
```

## Connecting to vagrant

```bash
$ vagrant ssh
```

## Disconnecting from vagrant

```bash
$ exit
```

# VirtualEnvWrapper

## Create virtual environment

```bash
$ mkvirtualenv <env_name> --python=python3
```

## Delete virtual environment

```bash
$ deactivate
$ rmvirtualenv <env_name>
```

## Activate virtual environment

```bash
$ workon <env_name>
```

# Dependencies

## Installing

```bash
$ pip install django==1.11
```

# Django

## Create project

```bash
src$ django-admin.py startproject profiles_project
```

## Create app

```bash
src$ python manage.py startapp profiles_api
```

## Updating requirements file

```bash
$ pip freeze > requirements.txt
```

## Creating migrations

```bash
/vagrant/src/profiles_project$ python manage.py makemigrations
/vagrant/src/profiles_project$ python manage.py migrate
```

## Creating super user

```bash
/vagrant/src/profiles_project$ python manage.py createsuperuser
```

## Starting the server

```bash
/vagrant/src/profiles_project$ python manage.py runserver 0.0.0.0:8080
```

Go to [http://localhost:8080/admin](http://localhost:8080/admin)

## ViewSets

- APIView
- Viewset
	- For simple CRUD interface
	- Little to no customization

