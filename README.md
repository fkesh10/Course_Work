# Tech prog Coursework

Katkov BIB2101

# Some useful commands to run this

pytho3n manage.py makemessages

pytho3n manage.py compilemessages

python3 manage.py makemigrations

python3 manage.py migrate

# RabbitMQ how to run (if u dockerized)

    $ docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.11-management

# How to run celery 

    $ celery -A myshop worker -l info

# Done:
1. Products
2. Cart
3. Order
4. Celery
