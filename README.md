robotablet-client
====

## Description

* [Server Application](https://github.com/shiraco/robotablet)
* [Client Application](https://github.com/shiraco/robotablet-client)

## Requirement

* [yyuu/pyenv](https://github.com/yyuu/pyenv)

* [python 2.7.x (use pyenv)](https://github.com/shiraco/robotablet-client/blob/master/.python-version)

* [pypa/virtualenv](https://github.com/pypa/virtualenv)

* [python library](https://github.com/shiraco/robotablet-client/blob/master/rrequirements.txt)

## Install

```
$ git clone https://github.com/shiraco/robotablet-client.git
```

## Usage

### Setup

```
$ cd /path/to/robotablet-client
$ pyenv local 2.7.11
$ virtualenv .venv
$ rm -rf robotablet-client/lib/*
$ .venv/bin/pip install -r requirements.txt --target robotablet-client/lib --no-compile
```

### Open with Choregraphe

Run Choregraphe and open robotablet-client/robotablet-client.pml .

### Configuration

Setting up below parameters.

* server host: (your robotablet-server host address)

### Run Application

Connect to the my tobot and run this application.

## Licence

[MIT License](https://github.com/shiraco/robotablet-client/blob/master/LICENSE)

## Author

[shiraco](https://github.com/shiraco)
