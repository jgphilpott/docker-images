# Pi Pack Base

The '[Pi Pack Base](https://github.com/jgphilpott/docker-images/tree/master/pi-series/pi-pack-base)' is a collection of software packages commonly used in Raspberry Pi projects.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/pi-pack:base`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/pi-pack:base`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.
 - [hickory](https://github.com/maxhumber/hickory) - A command line tool for scheduling Python scripts.
 - [Arrow](https://github.com/arrow-py/arrow) - Better dates & times for Python.
 - [spidev](https://github.com/doceme/py-spidev) - A Python module for interfacing with SPI devices.
 - [python-dotenv](https://github.com/theskumar/python-dotenv) - Get and set values in your .env file.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.
 - [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) - A Python SQL toolkit.

### Networking

 - [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - SocketIO integration for Flask applications.
 - [Eventlet](https://github.com/eventlet/eventlet) - A concurrent networking library for Python.

### Crawling

 - [HTTPie](https://github.com/jakubroztocil/httpie) - A simple command line tool for making HTTP requests.
 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [gazpacho](https://github.com/maxhumber/gazpacho) - A simple, fast and modern web scraping library.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for getting data out of HTML and XML files.

### GPIO

 - [gpiozero](https://github.com/gpiozero/gpiozero) - A simple Python interface for GPIO devices with Raspberry Pi.
 - [RPi.GPIO](https://github.com/Tieske/rpi-gpio) - A Python library for controlling a Raspberry Pi's GPIO pins.

### GUI

 - [guizero](https://github.com/lawsie/guizero) - A Python library for quickly and easily creating GUIs.
 - [colorzero](https://github.com/waveform80/colorzero) - A Python library for color manipulation.

### Sensory

 - [pi_analog](https://github.com/simonmonk/pi_analog) - A Python library for using resistive sensors with Raspberry Pi.
 - [picamera](https://github.com/waveform80/picamera) - A Python interface for the Raspberry Pi camera module.
 - [MFRC522](https://github.com/pimylifeup/MFRC522-python) - ...
 - [HX711](https://github.com/mpibpc-mroose/hx711) - ...
 - [Adafruit DHT](https://github.com/adafruit/DHT-sensor-library) - ...
 - [fingerprint](https://github.com/bastianraschke/pyfingerprint) - ...
 - [RdSpi](https://github.com/achilikin/RdSpi) - ...

### Image Processing

 - [Pillow](https://github.com/python-pillow/Pillow) - A Python imaging library.
 - [Python Tesseract](https://github.com/madmaze/pytesseract) - A Python tool for reading text embedded in images.

### Cryptography

 - [secure](https://github.com/TypeError/secure.py) - A library for adding security headers to Python web frameworks.
 - [ECDSA](https://github.com/warner/python-ecdsa) - A digital signature algorithm.
 - [RSA](https://github.com/sybrenstuvel/python-rsa) - An asymmetric key algorithm.
