# Python (SCL) S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-python-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-python-scl)

This repository contains the source for building various versions of
the Python application as a reproducible Docker image
[source-to-image](https://github.com/openshift/source-to-image)
to be run on [AusNimbus](https://www.ausnimbus.com.au/).

Images are built with Python RPM packages from SCL.
The resulting image can be run using [Docker](http://docker.io).

## Versions

The versions currently supported are:

- 2.7
- 3.3 (deprecated)
- 3.4
- 3.5
