# Profile REST API

REST API providing basic functionality for managing user profiles

Based on [Mark Winterbottom's Udemy course](https://www.udemy.com/django-python)

## Requirements
* Vagrant
* virtualbox

### Setting up Vagrant box (on the host machine):
```
$ vagrant init
$ vagrant up
$ vagrant ssh
$ vagrant halt
$ vagrant destroy

```

Files in the same directory as the Vagrantfile are synced to /vagrant/

### Setting up a virtual environment (on the Vagrant box):
```
$ mkvirtualenv profiles_api --python=python3
$ deactivate
$ workon profiles_api
```

### Install requirements
```
$ pip install django==1.11
$ pip install djangorestframework==3.6.2
```

### Start Django project
```
$ mkdir /vagrant/src/ && cd /vagrant/src/
$ django-admin.py startproject profiles_project
$ cd profiles_project
$ python manage.py startapp profiles_api
```

### Start Django Development Server
```
# listen on all IP Addresses
$ python manage.py runserver 0.0.0.0:8080
```
