# Getting started with Testcontainers for Python

This is sample code for [Getting started with Testcontainers for Python](https://testcontainers.com/guides/getting-started-with-testcontainers-for-python) guide.

## 1. Setup Environment

* Make sure you have a [compatible Docker environment](https://www.testcontainers.org/supported_docker_environment/) installed.
* Python 3.12+ installed.

For example:

```shell
$ python --version
Python 3.12.0
```

## 2. Setup Project

* Clone the repository

```shell
git clone https://github.com/testcontainers/tc-guide-getting-started-with-testcontainers-for-python.git
cd tc-guide-getting-started-with-testcontainers-for-python
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

* Open the **tc-guide-getting-started-with-testcontainers-for-python** project in your favorite IDE.

## 3. Run Tests

Run the command to run the tests.

```shell
$ pytest
```

The tests should pass.
