# nexchange
API for crypto currency exchange.

This Python package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 
- Package version: 1.0.0
- Build package: io.swagger.codegen.languages.PythonClientCodegen

## Requirements.

Python 2.7 and 3.4+

## Installation & Usage
### pip install

If the python package is hosted on Github, you can install directly from Github

```sh
pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git
```
(you may need to run `pip` with root permission: `sudo pip install git+https://github.com/GIT_USER_ID/GIT_REPO_ID.git`)

Then import the package:
```python
import nexchange 
```

### Setuptools

Install via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install --user
```
(or `sudo python setup.py install` to install the package for all users)

Then import the package:
```python
import nexchange
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```python
from __future__ import print_function
import time
import nexchange
from nexchange.rest import ApiException
from pprint import pprint
# create an instance of the API class
api_instance = nexchange.DefaultApi()

try:
    # Get Currencies
    api_instance.en_api_v1_currency_get()
except ApiException as e:
    print("Exception when calling DefaultApi->en_api_v1_currency_get: %s\n" % e)

```

## Documentation for API Endpoints

All URIs are relative to *https://nexchange.co.uk*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**en_api_v1_currency_get**](docs/DefaultApi.md#en_api_v1_currency_get) | **GET** /en/api/v1/currency/ | Get Currencies
*DefaultApi* | [**en_api_v1_orders_get**](docs/DefaultApi.md#en_api_v1_orders_get) | **GET** /en/api/v1/orders/ | Get Orders
*DefaultApi* | [**en_api_v1_orders_post**](docs/DefaultApi.md#en_api_v1_orders_post) | **POST** /en/api/v1/orders/ | Create Anonymous Order
*DefaultApi* | [**en_api_v1_orders_unique_reference_get**](docs/DefaultApi.md#en_api_v1_orders_unique_reference_get) | **GET** /en/api/v1/orders/{unique_reference}/ | Get Order
*DefaultApi* | [**en_api_v1_pair_get**](docs/DefaultApi.md#en_api_v1_pair_get) | **GET** /en/api/v1/pair/ | Get Pairs
*DefaultApi* | [**en_api_v1_price_pair_name_history_get**](docs/DefaultApi.md#en_api_v1_price_pair_name_history_get) | **GET** /en/api/v1/price/{pair_name}/history/ | Get Ticker History
*DefaultApi* | [**en_api_v1_price_pair_name_latest_get**](docs/DefaultApi.md#en_api_v1_price_pair_name_latest_get) | **GET** /en/api/v1/price/{pair_name}/latest/ | Get Latest Ticker
*DefaultApi* | [**en_api_v1_users_me_orders_get**](docs/DefaultApi.md#en_api_v1_users_me_orders_get) | **GET** /en/api/v1/users/me/orders/ | Get User Orders
*DefaultApi* | [**en_api_v1_users_me_orders_post**](docs/DefaultApi.md#en_api_v1_users_me_orders_post) | **POST** /en/api/v1/users/me/orders/ | Create User Order
*DefaultApi* | [**en_api_v1_users_me_orders_unique_reference_get**](docs/DefaultApi.md#en_api_v1_users_me_orders_unique_reference_get) | **GET** /en/api/v1/users/me/orders/{unique_reference}/ | Get User Order


## Documentation For Models



## Documentation For Authorization

 All endpoints do not require authorization.


## Author



