# Commands

## commands to install python-pip, django, rabbitmq, and celery

```bash
sudo apt-get install python3-pip -y
sudo apt install python3-virtualenv
sudo apt install python3.8-venv
python3 -m venv env_django_celery
source env_django_celery/bin/activate
pip install wheel
pip install Django==2.0.3
pip install celery==4.1.0
sudo apt-get install erlang -y
sudo apt-get install rabbitmq-server -y
service rabbitmq-server status
```

## create project on django

```bash
#create project
django-admin startproject django_celery

#create app
mkdir applications
cd applications
django-admin startapp taks
touch __init__.py

#run to migrate
cd ../django_celery/
./manage.py migrate
```