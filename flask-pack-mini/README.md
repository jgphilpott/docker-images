# Flask Pack Mini

This image is a lightweight version of the '[Flask Pack Base](https://github.com/jgphilpott/docker-images/tree/master/flask-pack-base)', a collection of software packages commonly used in Flask applications.

## Usage

To pull this image via the command line:

`sudo docker pull jgphilpott/flask-pack:mini`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/flask-pack:mini`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.

### Scraping

 - [HTTPie](https://github.com/jakubroztocil/httpie) - A simple command line tool for making HTTP requests.
 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for pulling data out of HTML and XML files.

### Cryptography

 - [Secure](https://github.com/TypeError/secure.py) - A Python library for securing request headers and cookies.
