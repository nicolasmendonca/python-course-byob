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



