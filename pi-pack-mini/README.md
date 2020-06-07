# Pi Pack Mini

This image is a lightweight version of the 'Pi Pack', a collection of software packages commonly used in Raspberry Pi projects.

## Usage

To pull this image via the command line:

`docker pull docker.pkg.github.com/jgphilpott/docker-images/pi-pack-mini:v1`

To use this image as the base in a Dockerfile:

`FROM docker.pkg.github.com/jgphilpott/docker-images/pi-pack-mini:v1`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### GPIO

 - [gpiozero](https://github.com/gpiozero/gpiozero) - A simple Python interface for GPIO devices with Raspberry Pi.

### GUI

 - [guizero](https://github.com/lawsie/guizero) - A Python library for quickly and easily creating GUIs.
 - [colorzero](https://github.com/waveform80/colorzero) - A Python library for color manipulation.
