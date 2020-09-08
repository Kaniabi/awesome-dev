# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Cloned from the original [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Python](#awesome-python)
    - [Admin Panels](#admin-panels)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [Audio](#audio)
    - [Authentication](#authentication)
    - [Build Tools](#build-tools)
    - [Built-in Classes Enhancement](#built-in-classes-enhancement)
    - [Caching](#caching)
    - [ChatOps Tools](#chatops-tools)
    - [CMS](#cms)
    - [Code Analysis](#code-analysis)
    - [Command-line Tools](#command-line-tools)
    - [Compatibility](#compatibility)
    - [Computer Vision](#computer-vision)
    - [Concurrency and Parallelism](#concurrency-and-parallelism)
    - [Configuration](#configuration)
    - [Cryptography](#cryptography)
    - [Data Analysis](#data-analysis)
    - [Data Validation](#data-validation)
    - [Data Visualization](#data-visualization)
    - [Database Drivers](#database-drivers)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Debugging Tools](#debugging-tools)
    - [Deep Learning](#deep-learning)
    - [DevOps Tools](#devops-tools)
    - [Distributed Computing](#distributed-computing)
    - [Distribution](#distribution)
    - [Documentation](#documentation)
    - [Downloader](#downloader)
    - [E-commerce](#e-commerce)
    - [Editor Plugins and IDEs](#editor-plugins-and-ides)
    - [Email](#email)
    - [Environment Management](#environment-management)
    - [Files](#files)
    - [Foreign Function Interface](#foreign-function-interface)
    - [Forms](#forms)
    - [Functional Programming](#functional-programming)
    - [Git](#git)
    - [Game Development](#game-development)
    - [Geolocation](#geolocation)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [HTML Manipulation](#html-manipulation)
    - [HTTP](#http)
    - [Image Processing](#image-processing)
    - [Implementations](#implementations)
    - [Interactive Interpreter](#interactive-interpreter)
    - [Internationalization](#internationalization)
    - [Job Scheduler](#job-scheduler)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [Networking](#networking)
    - [News Feed](#news-feed)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Package Repositories](#package-repositories)
    - [Permissions](#permissions)
    - [Processes](#processes)
    - [Queue](#queue)
    - [Recommender Systems](#recommender-systems)
    - [RESTful API](#restful-api)
    - [Robotics](#robotics)
    - [RPC Servers](#rpc-servers)
    - [Science](#science)
    - [Search](#search)
    - [Serialization](#serialization)
    - [Serverless Frameworks](#serverless-frameworks)
    - [Specific Formats Processing](#specific-formats-processing)
    - [Static Site Generator](#static-site-generator)
    - [Tagging](#tagging)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [URL Manipulation](#url-manipulation)
    - [Video](#video)
    - [Web Asset Management](#web-asset-management)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling & Web Scraping](#web-crawling--web-scraping)
    - [Web Frameworks](#web-frameworks)
    - [WebSocket](#websocket)
    - [WSGI Servers](#wsgi-servers)
- [Services](#services)
    - [Code Quality](#code-quality)
    - [Continuous Integration](#continuous-integration)
- [Resources](#resources)
    - [Podcasts](#podcasts)
    - [Twitter](#twitter)
    - [Websites](#websites)
    - [Weekly](#weekly)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

---

## Admin Panels

*Libraries for administrative interfaces.*

* [django-grappelli](http://grappelliproject.com) - A jazzy skin for the Django Admin-Interface.


## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*


## Audio

*Libraries for manipulating audio and its metadata.*

* Audio
* Metadata

## Authentication

*Libraries for implementing authentications schemes.*

* OAuth
    * [django-allauth](https://github.com/pennersr/django-allauth) - Authentication app for Django that "just works."
    * [django-social-auth]
* JWT
    * [pyjwt](https://github.com/jpadilla/pyjwt) - JSON Web Token implementation in Python.
    * [python-jose](https://github.com/mpdavis/python-jose/) - A JOSE implementation in Python.
    * [python-jwt](https://github.com/davedoesdev/python-jwt) - A module for generating and verifying JSON Web Tokens.

## Build Tools

*Compile software from source code.*


## Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - (Python standard library) Data classes.


## CMS

*Content Management Systems.*


## Caching

*Libraries for caching data.*


## ChatOps Tools

*Libraries for chatbot development.*

* [errbot](https://github.com/errbotio/errbot/) - The easiest and most popular chatbot to implement ChatOps.

## Code Analysis

*Tools of static analysis, linters and code quality checkers. See: [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* Code Analysis
* Code Linters
    * [flake8](https://pypi.python.org/pypi/flake8) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
    * [pylint](https://www.pylint.org/) - A fully customizable source code analyzer.
    * [pylama](https://github.com/klen/pylama) - A code audit tool for Python and JavaScript.
    * [pydocstyle](https://github.com/pycqa/pydocstyle) - Nice tool to check for docstrings formating.
* Code Formatters
    * [black](https://github.com/ambv/black) (CHEKC) - The uncompromising Python code formatter.
    * [yapf](https://github.com/google/yapf) (CHEKC) - Yet another Python code formatter from Google.
* Static Type Checkers
* Static Type Annotations Generators

## Command-line Tools

*Libraries for building command-line application.*

* Command-line Application Development
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
* Terminal Rendering
    * [colorama](https://pypi.python.org/pypi/colorama) - Cross-platform colored terminal text.
* Productivity Tools
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
* CLI Enhancements
    * [httpie](https://github.com/jakubroztocil/httpie) (CHECK) - A command line HTTP client, a user-friendly cURL replacement.
    * [saws](https://github.com/donnemartin/saws) (CHECK) - A Supercharged [aws-cli](https://github.com/aws/aws-cli).

* [screenfetch](https://github.com/KittyKatt/screenFetch) - Fetches system/theme information in terminal for Linux desktop screenshots.


## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

## Computer Vision

*Libraries for computer vision.*


## Concurrency and Parallelism

*Libraries for concurrent and parallel execution. See [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio).*

* [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.
* [eventlet](http://eventlet.net/) - Asynchronous framework with WSGI support.
* [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).
* [uvloop](https://github.com/MagicStack/uvloop) - Ultra fast implementation of `asyncio` event loop on top of `libuv`.

## Configuration

*Libraries for storing and parsing configuration options.*


## Cryptography

* [paramiko](https://github.com/paramiko/paramiko) - A Python (2.6+, 3.3+) implementation of the SSHv2 protocol, providing both client and server functionality.

## Data Analysis

*Libraries for data analyzing.*

* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation.

## Data Visualization

*Libraries for visualizing data. See: [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.

## Database

*Databases implemented in Python.*


## Database Drivers

*Libraries for connecting and operating databases.*

* MySQL - [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)
    * [mysqlclient](https://github.com/PyMySQL/mysqlclient-python) - MySQL connector with Python 3 support ([mysql-python](https://sourceforge.net/projects/mysql-python/) fork).
* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres)
    * [psycopg2](http://initd.org/psycopg/) - The most popular PostgreSQL adapter for Python.
* Other Relational Databases
    * [pymssql](http://www.pymssql.org/en/latest/) - A simple database interface to Microsoft SQL Server.
* NoSQL Databases
    * [redis-py](https://github.com/andymccurdy/redis-py) - The Python client for Redis.
* Asynchronous Clients
    * [aiomysql](https://github.com/aio-libs/aiomysql) -


## Date and Time

*Libraries for working with dates and times.*

* [dateutil](https://github.com/dateutil/dateutil) - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [pytz](https://launchpad.net/pytz) - World timezone definitions, modern and historical. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.


## Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
* Tracing
* Profiler
* Others
    * [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) - Display various debug information for Django.
    * [flask-debugtoolbar](https://github.com/mgood/flask-debugtoolbar) - A port of the django-debug-toolbar to flask.


## Deep Learning

*Frameworks for Neural Networks and Deep Learning. See: [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*


## DevOps Tools

*Software and libraries for DevOps.*

* [ansible](https://github.com/ansible/ansible) - A radically simple IT automation platform.
* [fabric](https://github.com/fabric/fabric) - A simple, Pythonic tool for remote execution and deployment.
* [supervisor](https://github.com/Supervisor/supervisor) - Supervisor process control system for UNIX.
* [terraform](https://www.terraform.io/) - Create (AWS) infrastructure from code.
  * [Atlantis](https://www.runatlantis.io/) - "Terraform Pull Request Automatiion."

## Containers

* [docker](https://docker.io/) - 
* [Docker Hub](https://hub.docker) - 
* [docker-compose](https://docs.docker.com/compose/) - Fast, isolated development environments using [Docker](https://www.docker.com/).
* [podman](https://podman.io/) - " Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System."
  It seems that CentOS 8 replaced docker with podman. This is a curious alternative for docker client.
  REFERENCE: https://youtu.be/N0hSn5EwW8w
* [cri-o](https://cri-o.io/) - "Lightweight container runtime for Kubernetes"

## Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* Batch Processing
* Stream Processing


## Distribution

*Libraries to create packaged executables for release distribution.*

* [py2exe](http://www.py2exe.org/) - Freezes Python scripts (Windows).
* [PyInstaller](https://github.com/pyinstaller/pyinstaller) - Converts Python programs into stand-alone executables (cross-platform).


## Documentation

*Libraries for generating project documentation.*

* [sphinx](https://github.com/sphinx-doc/sphinx/) - Python Documentation generator.
* [pycco](https://github.com/pycco-docs/pycco) - The literate-programming-style documentation generator.
* [byexample](https://byexamples.github.io/byexample/) - "a literate programming engine where you mix ordinary text and snippets of code in the same file"


## Downloader

*Downloading stuff.*

* [wget](https://www.gnu.org/software/wget/)
* [curl](https://curl.haxx.se/)
* [youtube-dl](https://rg3.github.io/youtube-dl/) - A small command-line program to download videos from YouTube.


## E-commerce

*Frameworks and libraries for e-commerce and payments.*


## Editor Plugins and IDEs

* Emacs
* Sublime Text
* Vim
* Visual Studio
* Visual Studio Code
* IDE
    * [PyCharm](https://www.jetbrains.com/pycharm/) - Commercial Python IDE by JetBrains. Has free community edition available.


## Email

*Libraries for sending and parsing email.*


## Environment Management

*Libraries for Python version and environment management.*

* [pipenv](https://github.com/kennethreitz/pipenv) - Sacred Marriage of Pipfile, Pip, & Virtualenv.
* [pyenv](https://github.com/pyenv/pyenv) - Simple Python version management.
* [venv](https://docs.python.org/3/library/venv.html) - (Python standard library in Python 3.3+) Creating lightweight virtual environments.
* [virtualenv](https://pypi.python.org/pypi/virtualenv) - A tool to create isolated Python environments.
* [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/)


## Files

*Libraries for file manipulation and MIME type detection.*

* [path.py](https://github.com/jaraco/path.py) - A module wrapper for [os.path](https://docs.python.org/3/library/os.path.html).
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) An cross-platform, object-oriented path library.
* [Unipath](https://github.com/mikeorr/Unipath) - An object-oriented approach to file/directory operations.
* [watchdog](https://github.com/gorakhargosh/watchdog) - API and shell utilities to monitor file system events.


## Foreign Function Interface

*Libraries for providing foreign function interface.*

* [ctypes](https://docs.python.org/3/library/ctypes.html) - (Python standard library) Foreign Function Interface for Python calling C code.
* [SWIG](http://www.swig.org/Doc1.3/Python.html) - Simplified Wrapper and Interface Generator.

## Forms

*Libraries for working with forms.*


## Functional Programming

*Functional Programming with Python.*


## Git

* [pre-commit](https://pre-commit.com/) - A framework for managing and maintaining multi-language pre-commit hooks.


## GUI

*Libraries for working with graphical user interface applications.*

* [PyQt](https://riverbankcomputing.com/software/pyqt/intro) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework, with support for both Qt v4 and Qt v5 frameworks.
* [PySide](https://wiki.qt.io/PySide) - Python bindings for the [Qt](http://www.qt.io/) cross-platform application and UI framework, supporting the Qt v4 framework.


## Game Development

*Awesome game development libraries.*

* [Pygame](http://www.pygame.org/news.html) - Pygame is a set of Python modules designed for writing games.


## Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [GeoDjango](https://docs.djangoproject.com/en/dev/ref/contrib/gis/) - A world-class geographic web framework.


## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.
* [lxml](http://lxml.de/) - A very fast, easy-to-use and versatile library for handling HTML and XML.


## HTTP

*Libraries for working with HTTP.*

* [grequests](https://github.com/kennethreitz/grequests) - requests + gevent for asynchronous HTTP requests.
* [httplib2](https://github.com/httplib2/httplib2) - Comprehensive HTTP client library.
* [requests](http://docs.python-requests.org/en/latest/) - HTTP Requests for Humans™.


## Hardware

*Libraries for programming with hardware.*


## Image Processing

*Libraries for manipulating images.*

* [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.


## Implementations

*Implementations of Python.*

* [CPython](https://github.com/python/cpython) - **Default, most widely used implementation of the Python programming language written in C.**
* [Jython](https://hg.python.org/jython) - Implementation of Python programming language written in Java for the Java virtual machine (JVM).
* [PyPy](https://bitbucket.org/pypy/pypy) - Implementation of the Python programming language written in RPython and translated into C. PyPy focuses on speed, efficiency and compatibility with the original CPython interpreter. The interpreter uses black magic to make Python very fast without having to add in additional type information.


## Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
    * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter)


## Internationalization

*Libraries for working with i18n.*


## Job Scheduler

*Libraries for scheduling jobs.*


## Logging

*Libraries for generating and working with logs.*


## Machine Learning

*Libraries for Machine Learning. See: [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*


## Microsoft Windows

*Python programming on Microsoft Windows.*

* [PyWin32](https://sourceforge.net/projects/pywin32/) - Python Extensions for Windows.


## Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*


## Natural Language Processing

*Libraries for working with human languages.*

- General
- Chinese


## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*


## Networking

*Libraries for networking programming.*

* [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    - [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio)


## News Feed

*Libraries for building user's activities.*


## ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
    * [Django Models](https://docs.djangoproject.com/en/dev/topics/db/models/) - A part of Django.
    * [SQLAlchemy](https://www.sqlalchemy.org/) - The Python SQL Toolkit and Object Relational Mapper.
        * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy)
* NoSQL Databases
    * [Awesome Python Models](https://github.com/grundic/awesome-python-models) (CHECK)


## Package Management

*Libraries for package and dependency management.*

* [pip](https://pip.pypa.io/en/stable/) - The Python package and dependency manager.
    * [PyPI](https://pypi.org/)
    * [pip-tools](https://github.com/jazzband/pip-tools) - A set of tools to keep your pinned Python dependencies fresh.
* [conda](https://github.com/conda/conda/) - Cross-platform, Python-agnostic binary package manager.


## Package Repositories

*Local PyPI repository server and proxies.*

* [devpi](https://github.com/devpi/devpi) - PyPI server and packaging/testing/release tool.


## Permissions

*Libraries that allow or deny users access to data or functionality.*


## Processes

*Libraries for starting and communicating with OS processes.*


## Queue

*Libraries for working with event and task queues.*

* [celery](http://www.celeryproject.org/) - An asynchronous task queue/job queue based on distributed message passing.


## Recommender Systems

*Libraries for building recommender systems.*


## RESTful API

*Libraries for developing RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
* Flask
    * [flask-restless](https://github.com/jfinkels/flask-restless) - Generating RESTful APIs for database models defined with SQLAlchemy.
* Pyramid
* Framework agnostic


## Robotics

*Libraries for robotics.*


## RPC Servers

*RPC-compatible servers.*


## Science

*Libraries for scientific computing.*

* [NetworkX](https://networkx.github.io/) - A high-productivity software for complex networks.
* [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
* [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.


## Serialization

*Libraries for serializing complex data types*


## Serverless Frameworks

*Frameworks for developing serverless Python code.*


## Specific Formats Processing

*Libraries for parsing and manipulating specific text formats.*

* General
* Office
    * [xlwt](https://github.com/python-excel/xlwt) / [xlrd](https://github.com/python-excel/xlrd) - Writing and reading data and formatting information from Excel files.
* PDF
    * [ReportLab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* Markdown
* YAML
    * [PyYAML](http://pyyaml.org/) - YAML implementations for Python.
    * [ruamel-yaml]
* CSV
* Archive

## Static Site Generator

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*


## Tagging

*Libraries for tagging items.*


## Template Engine

*Libraries and tools for templating and lexing.*

* [Jinja2](https://github.com/pallets/jinja) - A modern and designer friendly templating language.


## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool.
      * [pytest-mock]
      * [pytest-cov]
      * [pytest-raises]
    * [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.
    * [testfixtures](https://testfixtures.readthedocs.io) - Super usefull LogCapture and OutputCapture context managers.Ad
* Test Runners
    * [tox](https://tox.readthedocs.io/en/latest/) - Auto builds and tests distributions in multiple Python versions
* GUI / Web Testing
    * [Selenium](https://pypi.python.org/pypi/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.
    * [splinter](https://github.com/cobrateam/splinter) - Open source tool for testing web applications.
* Mock
    * [freezegun](https://github.com/spulec/freezegun) - Travel through time by mocking the datetime module.
    * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
* Object Factories
* Code Coverage
    * [coverage](https://pypi.python.org/pypi/coverage) - Code coverage measurement.
* Fake Data
* Error Handler
* Rest API
    * [tavern](https://taverntesting.github.io/) - Tool to test Rest APIs.
* Testing Sites
    * [localtest.me](http://readme.localtest.me/) - This site points to your local host (127.0.0.1) and its very usefull for testing applications locally
    * [ngrok](https://ngrok.com/) - One command for an instant, secure URL to your localhost server through any NAT or firewall. 

## Text Processing

*Libraries for parsing and manipulating plain texts.*

* General
    * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
* Slugify
* Unique identifiers
* Parser

## Third-party APIs

*Libraries for accessing third party services APIs. See: [List of Python API Wrappers and Libraries](https://github.com/realpython/list-of-python-api-wrappers).*

* [boto3](https://github.com/boto/boto3) - Python interface to Amazon Web Services.
* [google-api-python-client](https://github.com/google/google-api-python-client) - Google APIs Client Library for Python.

## URL Manipulation

*Libraries for parsing URLs.*


## Video

*Libraries for manipulating video and GIFs.*


## WSGI Servers

*WSGI-compatible web servers.*

* [gunicorn](https://github.com/benoitc/gunicorn) - Pre-forked, partly written in C.
* [uWSGI](https://uwsgi-docs.readthedocs.io/en/latest/) - A project aims at developing a full stack for building hosting services, written in C.


## Web Asset Management

*Tools for managing, compressing and minifying website assets.*


## Web Content Extracting

*Libraries for extracting web contents.*


## Web Crawling & Web Scraping

*Libraries to automate data extraction from websites.*

* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [scrapy](https://scrapy.org/) - A fast high-level screen scraping and web crawling framework.


## Web Frameworks

*Full stack web frameworks.*

* [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [awesome-django](https://github.com/shahraizali/awesome-django)
* [Flask](http://flask.pocoo.org/) - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask)
    * [connexion](https://connexion.readthedocs.io/en/latest/index.html) - Integrates OpenAPI with Flask.
* [Sanic](https://github.com/channelcat/sanic) - Web server framework using async.
* [Tornado](http://www.tornadoweb.org/en/latest/) - A Web framework and asynchronous networking library.


## WebSocket

*Libraries for working with WebSocket.*


# Services

Online tools and APIs to simplify development.

* [gitignore.io](http://gitignore.io/) - "Create useful .gitignore files for your project" 

## Continuous Integration

*See: [awesome-CIandCD](https://github.com/ciandcd/awesome-ciandcd#online-build-system).*

* [CircleCI](https://circleci.com/) - A CI service that can run very fast parallel testing. (GitHub only)
* [Travis CI](https://travis-ci.org) - A popular CI service for your open source and [private](https://travis-ci.com) projects. (GitHub only)


## Code Quality

* [Codecov](https://codecov.io/) - Code coverage dashboard.

# Resources

Where to discover new Python libraries.

## Podcasts


## Twitter


## Websites

* [Awesome Python @LibHunt](https://python.libhunt.com/)

## Weekly

* [Pycoder's Weekly](http://pycoders.com/)
* [Python Weekly](http://www.pythonweekly.com/)


# Unclassified

### [url2env](https://pypi.org/project/url2env/)

A small utility to genereate Postgresql environment variables from a database url.

```
$ url2env psql://joebloggs:secret@db.example.com:4433/blog
PGUSER=joebloggs
PGPASSWORD=secret
PGHOST=db.example.com
PGPORT=4433
PGDATABASE=blog
```

Using on docker entry-point:

```bash
eval `url2env $DATABASE_URL`
```
