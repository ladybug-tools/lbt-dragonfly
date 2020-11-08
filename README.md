
![Dragonfly](http://www.ladybug.tools/assets/img/dragonfly.png)

[![Build Status](https://travis-ci.com/ladybug-tools/lbt-dragonfly.svg?branch=master)](https://travis-ci.com/ladybug-tools/lbt-dragonfly)

[![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/downloads/release/python-270/) [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) [![IronPython](https://img.shields.io/badge/ironpython-2.7-red.svg)](https://github.com/IronLanguages/ironpython2/releases/tag/ipy-2.7.8/)

# lbt-dragonfly

Collection of all Dragonfly core Python libraries.

Note that this repository and corresponding Python package does not contain any
code and it simply exists to provide a shortcut for installing all of the dragonfly
core libraries together.

## Included Dragonfly Packages

Running `pip install lbt-dragonfly` will result in the installation of the following
dragonfly Python packages:

* [dragonfly-core](https://github.com/ladybug-tools/dragonfly-core)
* [dragonfly-energy](https://github.com/ladybug-tools/dragonfly-energy)

## All Ladybug and Honeybee Packages Are Also Included

Since dragonfly uses ladybug and honeybee, the following dependencies are also included:

* [lbt-ladybug](https://github.com/ladybug-tools/lbt-ladybug)
* [lbt-honeybee](https://github.com/ladybug-tools/lbt-honeybee)

## The CLI option

Running `pip install lbt-dragonfly[cli]` will ensure that all dependencies for the
command line interfaces (CLI) are also installed, including:

* [dragonfly-schema](https://github.com/ladybug-tools/dragonfly-schema)
* [honeybee-schema](https://github.com/ladybug-tools/honeybee-schema)
