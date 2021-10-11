FROM python:buster

ADD . /
WORKDIR /

RUN apt-get update
RUN apt-get upgrade -y

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# RUN apt-get install python-smbus i2c-tools wiringpi
