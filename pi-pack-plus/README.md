# Pi Pack Plus

This image is a heavy duty version of the 'Pi Pack', a collection of software packages commonly used in Raspberry Pi projects.

## Usage

To pull this image via the command line:

`docker pull docker.pkg.github.com/jgphilpott/docker-images/pi-pack-plus:v1`

To use this image as the base in a Dockerfile:

`FROM docker.pkg.github.com/jgphilpott/docker-images/pi-pack-plus:v1`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [NumPy](https://github.com/numpy/numpy) - A fundamental package for scientific computing in Python.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### GPIO

 - [gpiozero](https://github.com/gpiozero/gpiozero) - A simple Python interface for GPIO devices with Raspberry Pi.
 - [pi_analog](https://github.com/simonmonk/pi_analog) - A Python library for using resistive sensors with Raspberry Pi.

### HATs

 - [Sense HAT](https://github.com/astro-pi/python-sense-hat) - A Python module to control the Raspberry Pi Sense HAT.

### GUI

 - [guizero](https://github.com/lawsie/guizero) - A Python library for quickly and easily creating GUIs.
 - [colorzero](https://github.com/waveform80/colorzero) - A Python library for color manipulation.

### Networking

 - [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - SocketIO integration for Flask applications.
 - [Eventlet](https://github.com/eventlet/eventlet) - A concurrent networking library for Python.

### Scraping

 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for pulling data out of HTML and XML files.

### Cryptography

 - [Secure](https://github.com/TypeError/secure.py) - A Python library for securing request headers and cookies.
 - [SHA-256](https://pypi.org/project/sha256/) - A one-way hash algorithm.
 - [ECDSA](https://github.com/warner/python-ecdsa) - A digital signature algorithm.
 - [RSA](https://github.com/sybrenstuvel/python-rsa) - A asymmetric key algorithm.
