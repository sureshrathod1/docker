FROM python:3
#MKDIR /mydjango
WORKDIR /mydjango
ADD requirements.txt /mydjango
RUN pip install -r requirements.txt
COPY . /mydjango/
#CMD python manage.py runserver 0.0.0.0:8081

