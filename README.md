# Python (SCL) S2I Builder

[![Build Status](https://travis-ci.org/ausnimbus/s2i-python-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-python-scl)
[![Docker Repository on Quay](https://quay.io/repository/ausnimbus/s2i-python-scl/status "Docker Repository on Quay")](https://quay.io/repository/ausnimbus/s2i-python-scl)

This repository contains the source for the [source-to-image](https://github.com/openshift/source-to-image)
builders used to deploy [Python applications](https://www.ausnimbus.com.au/languages/python/)
on [AusNimbus](https://www.ausnimbus.com.au/).

The builders are built using Python binaries from [SCL](https://www.softwarecollections.org/en/)

If you are interested in using the latest Python versions, use [s2i-python](https://github.com/ausnimbus/s2i-python)

## Versions

The versions currently supported are:

- 2.7
- 3.4
- 3.5
