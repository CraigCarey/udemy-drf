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
```

Files in the same directory as the Vagrantfile are synced to /vagrant/

### Setting up a virtual environment (on the Vagrant box):
```
$ mkvirtualenv profiles_api --python=python3
$ deactivate
$ workon profiles_api
```
