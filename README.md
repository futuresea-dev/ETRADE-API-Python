# E*TRADE API Python Sample Application

This sample Python application provides examples on using the ETRADE API endpoints.

## Table of Contents

* [Requirements](#requirements)
* [Setup](#setup)
* [Running Code](#running-code)

## Requirements

In order to run this sample application you need the following three items:

1. Python 3 - this sample application is written in Python and requires Python 3. If you do not
already have Python 3 installed, download it from

   [`https://www.python.org/downloads/`](https://www.python.org/downloads/).

2. An [E*TRADE](https://us.etrade.com) account

3. E*TRADE consumer key and consumer secret.


## Setup

1. Unzip python zip file

2. Edit [`config.ini`](EtradePythonClient/etrade_python_client/config.ini)
with your consumer key and consumer secret; copy these from your application's keys' section

3. Create the virtual environment by running the Python's venv command; see the command syntax below

```
$ python3 -m venv venv
```

4. Activate the Python virtual environment

On Windows, run:

```
$ venv\Scripts\activate.bat
```

On Unix or Mac OS, run:

```
$ source venv/bin/activate
```

5. Use pip to install dependencies for the sample application

```
$ pip install -r requirements.txt
```

6. Run the sample application

```
$ cd etrade_python_client
$ python3 etrade_python_client.py
```

## Running Code

Complete these steps to run the code for the sample application:

1. Activate the Python virtual environment

On Windows, run:

```
$ venv\Scripts\activate.bat
```

On Unix or Mac OS, run:

```
$ source venv/bin/activate
```

2. Run the application

```
$ cd etrade_python_client
$ python3 etrade_python_client.py
```