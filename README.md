# Django Polls App

[![Build Status](https://app.travis-ci.com/yj3335/swe1-app.svg?branch=main)](https://app.travis-ci.com/yj3335/swe1-app)
[![Coverage Status](https://coveralls.io/repos/github/yj3335/swe1-app/badge.svg?branch=main)](https://coveralls.io/github/yj3335/swe1-app?branch=main)

A Django polls application built following the official Django tutorial!

## Setup

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Running Tests

```bash
python manage.py test
```

## Code Quality

```bash
black --check .
flake8 .
```

## CI/CD

This project uses Travis CI for continuous integration and deployment to AWS Elastic Beanstalk.
