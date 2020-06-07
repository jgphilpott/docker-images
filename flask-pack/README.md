# Flask Pack

The 'Flask Pack' is a collection of software packages commonly used in Flask applications.

## Usage

To pull this image via the command line:

`docker pull docker.pkg.github.com/jgphilpott/docker-images/flask-pack:v5`

To use this image as the base in a Dockerfile:

`FROM docker.pkg.github.com/jgphilpott/docker-images/flask-pack:v5`

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

### User Management

 - [Flask-Login](https://github.com/maxcountryman/flask-login) - User management for Flask applications.
 - [Flask-Session](https://github.com/fengsp/flask-session) - A server side session extension for Flask.

### Styling

 - [LibSass](https://github.com/sass/libsass-python) - A Sass compiler.

### Scraping

 - [HTTPie](https://github.com/jakubroztocil/httpie) - A simple command line tool for making HTTP requests.
 - [Scrapy](https://github.com/scrapy/scrapy) - A Python web crawling & scraping framework.
 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for pulling data out of HTML and XML files.

### Cryptography

 - [Secure](https://github.com/TypeError/secure.py) - A Python library for securing request headers and cookies.
 - [SHA-256](https://pypi.org/project/sha256/) - A one-way hash algorithm.
 - [ECDSA](https://github.com/warner/python-ecdsa) - A digital signature algorithm.
 - [RSA](https://github.com/sybrenstuvel/python-rsa) - A asymmetric key algorithm.
