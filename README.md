Flash REST API template
=======================

This repository contains a template for building REST APIs based on Flask.

It is based on layout recommended by Miguel Grinberg on the 
[git repo](https://github.com/miguelgrinberg/oreilly-flask-apis-video.git)
of the [Building Web APIs with Flask](http://bit.ly/flaskapi) course.

```
git clone https://github.com/javicacheiro/rest_api_flask.git
cd rest_api_flask
virtualenv venv
pip install -r requirements.txt
```

To add new REST resources create new modules inside rest/app/api_v1 
and add them to \_\_init\_\_.py:

    from . import products, newresource
