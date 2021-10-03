# Flask Pack Plus

This image is a heavy duty version of the '[Flask Pack Base](https://github.com/jgphilpott/docker-images/tree/master/flask-series/flask-pack-base)', a collection of software packages commonly used in Flask applications.

## Usage

To pull this image via the command line:

`docker pull jgphilpott/flask-pack:plus`

To use this image as the base in a Dockerfile:

`FROM jgphilpott/flask-pack:plus`

## Contents

### Core

 - [Flask](https://github.com/pallets/flask) - A Python micro framework for building web applications.
 - [Fire](https://github.com/google/python-fire) - A Python tool for generating command line interfaces.
 - [tqdm](https://github.com/tqdm/tqdm) - A Python tool for generating progress bars in the command line.
 - [hickory](https://github.com/maxhumber/hickory) - A command line tool for scheduling Python scripts.
 - [Arrow](https://github.com/arrow-py/arrow) - Better dates & times for Python.
 - [python-dotenv](https://github.com/theskumar/python-dotenv) - Get and set values in your .env file.

### Testing

 - [pytest](https://github.com/pytest-dev/pytest) - A simple and flexible framework for testing in Python.

### Database

 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - A Python driver for MongoDB.
 - [SQLAlchemy](https://github.com/sqlalchemy/sqlalchemy) - A Python SQL toolkit.

### Networking

 - [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - SocketIO integration for Flask applications.
 - [Eventlet](https://github.com/eventlet/eventlet) - A concurrent networking library for Python.

### User Management

 - [Flask-Login](https://github.com/maxcountryman/flask-login) - User management for Flask applications.
 - [Flask-Session](https://github.com/fengsp/flask-session) - A server side session extension for Flask.

### Styling

 - [LibSass](https://github.com/sass/libsass-python) - A Python Sass compiler.
 - [Boussole](https://github.com/sveetch/boussole) - A command line interface for building Sass projects.

### Communications

 - [Flask-Mail](https://github.com/mattupstate/flask-mail) - Simple SMTP integration to provide email capabilities in Flask applications.

### Scraping

 - [HTTPie](https://github.com/jakubroztocil/httpie) - A simple command line tool for making HTTP requests.
 - [Requests](https://github.com/psf/requests) - A Python library for making HTTP requests.
 - [gazpacho](https://github.com/maxhumber/gazpacho) - A simple, fast and modern web scraping library.
 - [BeautifulSoup4](https://code.launchpad.net/beautifulsoup) - A Python library for getting data out of HTML and XML files.
 - [Scrapy](https://github.com/scrapy/scrapy) - A Python web crawling & scraping framework.
 - [Selenium](https://github.com/SeleniumHQ/selenium) - A browser automation framework and ecosystem.
 - [The Wayback Machine Scraper](https://github.com/sangaline/wayback-machine-scraper) - A command-line utility for scraping data from [Archive.org's Wayback Machine](https://web.archive.org).

### Data Visualization

 - [Matplotlib](https://github.com/matplotlib/matplotlib) - A 2D plotting library for Python.
 - [Altair](https://github.com/altair-viz/altair) - A statistical visualization library for Python.
 - [plotly.py](https://github.com/plotly/plotly.py) - An interactive graphing library for Python.
 - [seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization in Python.

### Data Science Toolkit

 - [NumPy](https://github.com/numpy/numpy) - A fundamental package for scientific computing in Python.
 - [SciPy](https://github.com/scipy/scipy) - A NumPy extension.
 - [pandas](https://github.com/pandas-dev/pandas) - A flexible and powerful data analysis library.
 - [scikit-learn](https://github.com/scikit-learn/scikit-learn) - Machine learning in Python.
 - [statsmodels](https://github.com/statsmodels/statsmodels) - Statistical modeling and econometrics in Python.

### Neural Networking

#### TensorFlow

 - [TensorFlow](https://github.com/tensorflow/tensorflow) - A Python library for deep learning and neural networks.
 - [TensorFlow Hub](https://github.com/tensorflow/hub) - A library for transfer learning by reusing parts of TensorFlow models.
 - [Keras](https://github.com/keras-team/keras) - A user friendly interface for TensorFlow.

#### PyTorch

 - [PyTorch](https://github.com/pytorch/pytorch) - Tensors and dynamic neural networks in Python.
 - [PyTorch Text](https://github.com/pytorch/text) - Data loaders and abstractions for text and NLP.
 - [PyTorch Vision](https://github.com/pytorch/vision) - Datasets, Transforms and Models specific to computer vision.

### Natural Language Processing

 - [NLTK](https://github.com/nltk/nltk) - Natural Language Toolkit (NLTK).
 - [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans.
 - [polyglot](https://github.com/aboSamoor/polyglot) - Multilingual text (NLP) processing toolkit.

### Image Processing

 - [Pillow](https://github.com/python-pillow/Pillow) - A Python imaging library.
 - [Python Tesseract](https://github.com/madmaze/pytesseract) - A Python tool for reading text embedded in images.

### Cryptography

 - [secure](https://github.com/TypeError/secure.py) - A library for adding security headers to Python web frameworks.
 - [SHA-256](https://pypi.org/project/sha256) - A one-way hash algorithm.
 - [ECDSA](https://github.com/warner/python-ecdsa) - A digital signature algorithm.
 - [RSA](https://github.com/sybrenstuvel/python-rsa) - An asymmetric key algorithm.
