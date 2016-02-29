nao-grape-client
====

## Description

* [Server Application](https://github.com/tech-sketch/nao-grape-server)
* [Client Application](https://github.com/tech-sketch/nao-grape-client)

## Requirement

* [yyuu/pyenv](https://github.com/yyuu/pyenv)

* [python 2.7.x (use pyenv)](https://github.com/tech-sketch/nao-grape-client/blob/master/.python-version)

* [pypa/virtualenv](https://github.com/pypa/virtualenv)

* [python library](https://github.com/tech-sketch/nao-grape-client/blob/master/rrequirements.txt)

## Install

```
$ git clone https://github.com/tech-sketch/nao-grape-client.git
```

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

[Tech-Sketch](https://github.com/tech-sketch)
