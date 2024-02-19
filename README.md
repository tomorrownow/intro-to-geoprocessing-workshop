# intro-to-geoprocessing-workshop

Introduction to geoprocessing with GRASS GIS workshop.

## Local Setup

```bsah
# clone the forked repository
$ git clone YOUR_FORKED_REPO_URL

# create a virtual environment
$ python3 -m venv venv
# activate the virtual environment
$ source venv/bin/activate
# install django-extensions in development mode
(venv) $ pip install -e .
# install dependencies
(venv) $ pip install Django -r requirements-dev.txt

(venv) $ python manage.py runserver
```
