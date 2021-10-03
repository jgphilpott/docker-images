FROM jgphilpott/flask-pack:mini

ADD . /
WORKDIR /

RUN apt-get update
RUN apt-get upgrade -y

RUN pip install --upgrade pip

RUN pip install -r requirements.txt
