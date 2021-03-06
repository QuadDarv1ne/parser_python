# parser_python

[![rq-dashboard](https://img.shields.io/github/pipenv/locked/dependency-version/metabolize/rq-dashboard-on-heroku/rq-dashboard?style=flat-square)][pipfile]
[![python](https://img.shields.io/github/pipenv/locked/python-version/metabolize/rq-dashboard-on-heroku?style=flat-square)][pipfile]
![PyPI - License](https://img.shields.io/pypi/l/free?style=flat-square)
[![build](https://img.shields.io/circleci/project/github/metabolize/rq-dashboard-on-heroku?style=flat-square)][build]
[![code style](https://img.shields.io/badge/code%20style-black-black.svg?style=flat-square)][black]
<img alt="Mozilla Add-on" src="https://img.shields.io/amo/rating/dustman?style=flat-square&logo=appveyor">

[![followers](https://img.shields.io/github/followers/QuadDarv1ne?style=social)][pipfile]
[![status](https://img.shields.io/uptimerobot/status/m778918918-3e92c097147760ee39d02d36)][pipfile]

[pipfile]: https://github.com/metabolize/rq-dashboard-on-heroku/blob/master/Pipfile
[build]: https://circleci.com/gh/metabolize/rq-dashboard-on-heroku/tree/master
[black]: https://black.readthedocs.io/en/stable/

A version of [RQ Dashboard][] that can be deployed to Heroku.

[rq dashboard]: https://github.com/eoranged/rq-dashboard


## Deployment

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


## Configuration

Three settings must be configured:

- `RQ_DASHBOARD_REDIS_URL=rediss://`
- `RQ_DASHBOARD_USERNAME=user`
- `RQ_DASHBOARD_PASSWORD=pass`

Developing
----------

Develop in a virtualenv and make sure you have all the necessary build
time (and run time) dependencies with

    $ pip install -r requirements.txt

Develop in the normal way with

    $ python setup.py develop
    
    $ python sqlpython.py
    
## License 

This project is licensed | FREE License.
