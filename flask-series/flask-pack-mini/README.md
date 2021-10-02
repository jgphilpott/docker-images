# Flask Pack Mini

This image is a lightweight version of the '[Flask Pack Base](https://github.com/jgphilpott/docker-images/tree/master/flask-series/flask-pack-base)', a collection of software packages commonly used in Flask applications.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/flask-pack:mini`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/flask-pack:mini`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.
 - [hickory](https://github.com/maxhumber/hickory) - A command line tool for scheduling Python scripts.
 - [Arrow](https://github.com/arrow-py/arrow) - Better dates & times for Python.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.
 - [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) - A Python SQL toolkit.

### Styling

 - [LibSass](https://github.com/sass/libsass-python) - A Python Sass compiler.

### Scraping

 - [HTTPie](https://github.com/jakubroztocil/httpie) - A simple command line tool for making HTTP requests.
 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [gazpacho](https://github.com/maxhumber/gazpacho) - A simple, fast and modern web scraping library.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for getting data out of HTML and XML files.

### Image Processing

 - [Pillow](https://github.com/python-pillow/Pillow) - A Python Imaging Library.

### Cryptography

 - [secure](https://github.com/TypeError/secure.py) - A library for adding security headers to Python web frameworks.
