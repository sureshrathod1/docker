FROM python:3.8.5
copy . /app
WORKDIR /app
RUN apt update && apt add python3 python3-dev mariadb-dev build-base && pip3 install mysqlclient && apt del python3-dev mariadb-dev build-base
RUN pip install Django==3.0.8 django-mysql==3.8.1 

