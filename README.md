# tributary
Python Streams

[![Build Status](https://travis-ci.org/timkpaine/tributary.svg?branch=master)](https://travis-ci.org/timkpaine/tributary)
[![GitHub issues](https://img.shields.io/github/issues/timkpaine/tributary.svg)]()
[![codecov](https://codecov.io/gh/timkpaine/tributary/branch/master/graph/badge.svg)](https://codecov.io/gh/timkpaine/tributary)
[![BCH compliance](https://bettercodehub.com/edge/badge/timkpaine/tributary?branch=master)](https://bettercodehub.com/)
[![PyPI](https://img.shields.io/pypi/l/tributary.svg)](https://pypi.python.org/pypi/tributary)
[![PyPI](https://img.shields.io/pypi/v/tributary.svg)](https://pypi.python.org/pypi/tributary)
[![Docs](https://img.shields.io/readthedocs/tributary.svg)](https://tributary.readthedocs.io)


## Python Data Streams
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/example.gif)


# Stream Types
Tributary offers several kinds of streams:

## Reactive
These are synchronous, reactive data streams, built using python generators

## Asynchronous
These are asynchronous, reactive data streams, built using asynchronous python generators

## Functional
These are functional streams, built by currying python functions (callbacks)

## Lazy (work in progress)
These are lazily-evaluated python streams, where outputs are propogated only as inputs change.

# Examples
## Reactive
### Simple Example
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/example1.png)

### More Complex Example
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/example2.png)

### Rolling Mean
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/example3.png)

### Custom Calculations and Window Functions
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/example4.png)


## Sources
### WebSocket
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/ws.png)

### HTTP
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/http.png)

### SocketIO
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/sio.png)

### Kafka
![](https://raw.githubusercontent.com/timkpaine/tributary/master/docs/kafka.png)

## Sinks
### HTTP
### Kafka

