# Commands

## commands to install python-pip, django, rabbitmq, and celery

```bash
sudo apt-get install python3-pip -y
sudo apt install python3-virtualenv
sudo apt install python3.8-venv
python3 -m venv env_django_celery
pip install django
pip install Celery
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
```