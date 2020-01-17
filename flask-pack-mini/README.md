# Flask Pack Mini

This image is a lightweight version of the 'Flask Pack', a collection of software packages commonly used in Flask applications.

## Useage

To pull this image via the command line:

`docker pull docker.pkg.github.com/jgphilpott/docker-images/flask-pack-mini:v4`

To use this image as the base in a Dockerfile:

`FROM docker.pkg.github.com/jgphilpott/docker-images/flask-pack-mini:v4`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python command line tool.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### Scraping

 - [Requests](https://github.com/psf/requests) - A simple HTTP library.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for pulling data out of HTML and XML files.
