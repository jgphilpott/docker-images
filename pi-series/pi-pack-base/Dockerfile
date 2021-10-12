FROM jgphilpott/pi-pack:mini

ADD . /
WORKDIR /

RUN apt-get update
RUN apt-get upgrade -y

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

# RUN apt-get install python3-fingerprint

RUN git clone https://github.com/simonmonk/pi_analog.git
WORKDIR /pi_analog
RUN python3 setup.py install
WORKDIR /

RUN git clone https://github.com/achilikin/RdSpi.git
WORKDIR /RdSpi
RUN make
WORKDIR /
