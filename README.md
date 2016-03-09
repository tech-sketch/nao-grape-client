nao-grape-client
====

## Description

* Server Application (nao-grape-server)
* Client Application (nao-grape-client)
* Client Application Demo (nao-grape-client-demo)

## Requirement

* Multiple Python Virtual Environment
* Python Runtime
* Python Virtual Environment
* Dependency Libraries


### Multiple Python Virtual Environment

* [yyuu/pyenv](https://github.com/yyuu/pyenv) [Linux/Mac]
* [Miniconda](http://conda.pydata.org/miniconda.html) [Windows]

### Python Runtime

python 2.7.x

* use pyenv [Linux/Mac]

```
$ pyenv install -l
$ pyenv install 2.7.11
```

* install with Miniconda [Windows]

### Python Virtual Environment

* [pypa/virtualenv](https://github.com/pypa/virtualenv) [Linux/Mac/Windows]

```
$ pip install virtualenv
```

### Python Virtual Environment

* [pypa/virtualenv](https://github.com/pypa/virtualenv)

```
$ pip install virtualenv
```

### Dependency Libraries

* python library

See requirements.txt

## Install

## Usage

### Setup

* [Linux/Mac]

```
$ cd /path/to/nao-grape-client
$ pyenv local 2.7.11
$ rm -rf robotablet-client/lib/*
$ pip install -r requirements.txt --target robotablet-client/lib --no-compile
```

* [Windows]

```
$ cd /path/to/nao-grape-client
$ rm -rf robotablet-client/lib/*
$ pip install -r requirements.txt --target robotablet-client/lib --no-compile
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
