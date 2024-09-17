FROM jgphilpott/node-pack:base

COPY ./ /usr/app
WORKDIR /usr/app

RUN apt-get update
RUN apt-get upgrade -y

RUN npm install
