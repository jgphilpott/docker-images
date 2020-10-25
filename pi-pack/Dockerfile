FROM jgphilpott/pi-pack:mini

RUN pip install --upgrade pip

RUN pip install python-dotenv

RUN pip install Flask-SocketIO
RUN pip install Eventlet

RUN pip install requests
RUN pip install beautifulsoup4

RUN git clone https://github.com/simonmonk/pi_analog.git
WORKDIR /pi_analog
RUN python3 setup.py install
WORKDIR /

RUN pip install  picamera

RUN pip install sha256
RUN pip install ecdsa
RUN pip install rsa
