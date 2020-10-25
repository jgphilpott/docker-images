# Pi Pack Plus

This image is a heavy duty version of the '[Pi Pack Base](https://github.com/jgphilpott/docker-images/tree/master/pi-pack-base)', a collection of software packages commonly used in Raspberry Pi projects.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/pi-pack:plus`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/pi-pack:plus`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.
 - [python-dotenv](https://github.com/theskumar/python-dotenv) - Get and set values in your .env file.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### Networking

 - [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - SocketIO integration for Flask applications.
 - [Eventlet](https://github.com/eventlet/eventlet) - A concurrent networking library for Python.

### Crawling

 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for pulling data out of HTML and XML files.

### GPIO

 - [gpiozero](https://github.com/gpiozero/gpiozero) - A simple Python interface for GPIO devices with Raspberry Pi.
 - [RPi.GPIO](https://github.com/Tieske/rpi-gpio) - A Python library for controlling a Raspberry Pi's GPIO pins.

### GUI

 - [guizero](https://github.com/lawsie/guizero) - A Python library for quickly and easily creating GUIs.
 - [colorzero](https://github.com/waveform80/colorzero) - A Python library for color manipulation.

### HATs

 - [Sense HAT](https://github.com/astro-pi/python-sense-hat) - A Python module to control the Raspberry Pi Sense HAT.

### Sensory

 - [pi_analog](https://github.com/simonmonk/pi_analog) - A Python library for using resistive sensors with Raspberry Pi.
 - [picamera](https://github.com/waveform80/picamera) - A Python interface for the Raspberry Pi camera module.

### Cryptography

 - [Secure](https://github.com/TypeError/secure.py) - A Python library for securing request headers and cookies.
 - [SHA-256](https://pypi.org/project/sha256/) - A one-way hash algorithm.
 - [ECDSA](https://github.com/warner/python-ecdsa) - A digital signature algorithm.
 - [RSA](https://github.com/sybrenstuvel/python-rsa) - A asymmetric key algorithm.
