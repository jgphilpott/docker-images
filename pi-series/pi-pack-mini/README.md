# Pi Pack Mini

This image is a lightweight version of the '[Pi Pack Base](https://github.com/jgphilpott/docker-images/tree/master/pi-series/pi-pack-base)', a collection of software packages commonly used in Raspberry Pi projects.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/pi-pack:mini`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/pi-pack:mini`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### GPIO

 - [gpiozero](https://github.com/gpiozero/gpiozero) - A simple Python interface for GPIO devices with Raspberry Pi.
 - [RPi.GPIO](https://github.com/Tieske/rpi-gpio) - A Python library for controlling a Raspberry Pi's GPIO pins.

### GUI

 - [guizero](https://github.com/lawsie/guizero) - A Python library for quickly and easily creating GUIs.
 - [colorzero](https://github.com/waveform80/colorzero) - A Python library for color manipulation.

### Cryptography

 - [Secure](https://github.com/TypeError/secure.py) - A Python library for securing request headers and cookies.
