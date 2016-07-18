# hark-builder

[![Build Status](https://travis-ci.org/hark-project/hark-builder.svg?branch=develop)](https://travis-ci.org/hark-project/hark-builder)

This repository contains scripts and configuration to build machine images used
by the [hark project](https://hark-project.net).

The images produced by these scripts are uploaded to Amazon S3 and served by
the [hark-imagestore](https://github.com/hark-project/hark-imagestore) service,
which are downloaded and stored locally by the client-side
[hark](https://github.com/hark-project) tool.

# Dependencies

The hark-builder tool requires `packer`, which needs to be installed manually -
it cannot be provided by Python.

Packer can be downloaded from <https://www.packer.io/>.

# Python Support

Same as the main hark tool - see the [README#Python
Support](https://github.com/hark-project/hark#python-support).

# Running Tests

Again, same as the main hark tool - see its [README#Running
Tests](https://github.com/hark-project/hark#running-tests).

# License

GPLv3. See the LICENSE file for details.

