FROM python:3.8

RUN pip install --upgrade pip

RUN pip install Flask
RUN pip install numpy
RUN pip install fire
RUN pip install tqdm

RUN pip install pytest

RUN pip install pymongo

RUN pip install gpiozero
RUN git clone https://github.com/simonmonk/pi_analog.git
WORKDIR /pi_analog
RUN python3 setup.py install
WORKDIR /

RUN pip install guizero
RUN pip install colorzero

RUN pip install requests
RUN pip install beautifulsoup4

RUN pip install secure
