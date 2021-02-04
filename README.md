
![Dragonfly](http://www.ladybug.tools/assets/img/dragonfly.png)

[![Build Status](https://github.com/ladybug-tools/lbt-dragonfly/workflows/CI/badge.svg)](https://github.com/ladybug-tools/lbt-dragonfly/actions)

[![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/downloads/release/python-270/) [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) [![IronPython](https://img.shields.io/badge/ironpython-2.7-red.svg)](https://github.com/IronLanguages/ironpython2/releases/tag/ipy-2.7.8/)

# lbt-dragonfly

Collection of all Dragonfly core Python libraries.

Note that this repository and corresponding Python package does not contain any
code and it simply exists to provide a shortcut for installing all of the dragonfly
core libraries together.

## Included Dragonfly Extensions

Running `pip install lbt-dragonfly` will result in the installation of the following
dragonfly Python packages:

* [dragonfly-uwg](https://github.com/ladybug-tools/dragonfly-uwg)
* [dragonfly-energy](https://github.com/ladybug-tools/dragonfly-energy)

## Included Dragonfly Core Libraries

Since both dragonfly extensions use the dragonfly core libraries, the following
dependencies are also included:

* [dragonfly-core](https://github.com/ladybug-tools/dragonfly-core)
* [dragonfly-schema](https://github.com/ladybug-tools/dragonfly-schema)

## All Ladybug and Honeybee Packages Are Also Included

Since dragonfly uses ladybug and honeybee, the following dependencies are also included:

* [lbt-ladybug](https://github.com/ladybug-tools/lbt-ladybug)
* [lbt-honeybee](https://github.com/ladybug-tools/lbt-honeybee)
