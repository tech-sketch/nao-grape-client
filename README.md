nao-grape-client
====

## Description

* Server Application (nao-grape-server)
* Client Application (nao-grape-client)
* Client Application Demo (nao-grape-client-demo)

## Requirement

* [yyuu/pyenv](https://github.com/yyuu/pyenv)
* python 2.7.x (use pyenv)
* [pypa/virtualenv](https://github.com/pypa/virtualenv)
* python library

## Install

## Usage

### Setup

```
$ cd /path/to/nao-grape-client
$ pyenv local 2.7.11
$ virtualenv .venv
$ rm -rf robotablet-client/lib/*
$ .venv/bin/pip install -r requirements.txt --target robotablet-client/lib --no-compile
```

### Open with Choregraphe

Run Choregraphe and open robotablet-client/robotablet-client.pml .

### Configuration

Setting up below parameters.

* server host: (your server host address)

### Run Application

Connect to the my robot and run this application.

## Author

[TIS Inc.](http://www.tis.co.jp/)
