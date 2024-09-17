FROM node:latest

COPY ./ /usr/app
WORKDIR /usr/app

RUN apt-get update
RUN apt-get upgrade -y

RUN apt-get install -y wget curl

RUN npm install
