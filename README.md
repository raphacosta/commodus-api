# gamification-engine
[![Build Status](https://travis-ci.org/ActiDoo/gamification-engine.svg?branch=master)](https://travis-ci.org/ActiDoo/gamification-engine)
[![Coverage Status](https://coveralls.io/repos/github/ActiDoo/gamification-engine/badge.svg?branch=master)](https://coveralls.io/github/ActiDoo/gamification-engine?branch=master)
[![Requirements Status](https://requires.io/github/ActiDoo/gamification-engine/requirements.svg?branch=master)](https://requires.io/github/ActiDoo/gamification-engine/requirements/?branch=master)
[![Heroku](https://heroku-badge.herokuapp.com/?app=gamification-engine&root=admin/)](https://gamification-engine.herokuapp.com)
[![Documentation Status](https://img.shields.io/badge/docs-master-brightgreen.svg?style=flat)](https://readthedocs.org/projects/gamification-engine/?badge=master)
[![Release](https://img.shields.io/github/release/ActiDoo/gamification-engine.svg?style=flat)](https://github.com/ActiDoo/gamification-engine/releases/latest)
[![Latest Version](https://badge.fury.io/py/gamification-engine.svg)](https://pypi.python.org/pypi/gamification-engine/)
[![PyPI](https://img.shields.io/pypi/pyversions/gamification-engine.svg)]()
[![License](http://img.shields.io/:license-mit-green.svg)](https://github.com/ActiDoo/gamification-engine/blob/master/LICENSE)
<!--[![Downloads](https://img.shields.io/pypi/dm/gamification-engine.svg)](https://pypi.python.org/pypi/gamification-engine/)-->

The Commodus API (cengine) is an enterprise software for integrating any kinds of gamification features into your product.

## Features

- multi level achievements
- multi goal achievements
- progress and single goals 
- leader boards / ladder
- achievements can be reached directly or by evaluating leaderboards daily, weekly, monthly or yearly
- time zone independent (correct daily, weekly.. evaluations among time zones)
- social-awareness (e.g. reach the highest score among your friends)
- geo-awareness (e.g. reach the highest score among all users in your city)
- rules can be defined in python using given variables (e.g. the current level)
- custom definable achievement properties and rewards
- custom definable languages and translations
- dependencies between achievements (prerequisites & postconditions)
- goals can execute triggers (currently creation of messages and mobile pushes for iOS/Android)
- high performance / scalable

## REST Interface

Simple REST-interface to communicate with arbitrary systems

see http://commodus.readthedocs.org/en/latest/rest/index.html


## Roadmap

For a full list see:

http://commodus.readthedocs.org/en/latest/roadmap.html

## Licenses of dependencies

Pyramid: BSD-derived (http://www.repoze.org/LICENSE.txt)

pyramid_chameleon: BSD-derived (http://www.repoze.org/LICENSE.txt)

pyramid_debugtoolbar: BSD

SQLAlchemy: MIT

zope.sqlalchemy: Zope Public License (ZPL) Version 2.1

waitress: Zope Public License (ZPL) Version 2.1

pytz: MIT

dogpile.cache: BSD

pyramid_dogpile_cache: MIT

flask: BSD

flask-admin: BSD

psycopg2: LGPL / ZPL

pymemcache: Apache License 2.0

mock: BSD

alembic: MIT
