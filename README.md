## README.md

This repository contains the source code the example website used throughout the book *Web Scraping with Python*, published by Packt Publishing. When run locally the app will not block IP's that download faster than the thresholds specified in *models/3_cache.db*, which means you can test your crawler faster.

## Install

This app relies on the *web2py* framework, which can be [downloaded here](http://web2py.com/init/default/download) and is [documented here](http://web2py.com/book).

In the shell the installation instructions are as follows:

```
#!bash

    # first download web2py
    wget http://www.web2py.com/examples/static/web2py_src.zip
    unzip web2py_src.zip
    # now download the app
    cd web2py/applications
    git clone git@github.com:richardpenman/wswp_places.git places
    # now start the web2py server with a password for the admin interface
    cd ..
    python web2py.py --password=<password>
```

The places app can now be accessed in your web browser at http://127.0.0.1:8000/places.

> Note: Must use Python 2 to run the website.

## Run

```shell
$ cd web2py
$ python web2py.py
```