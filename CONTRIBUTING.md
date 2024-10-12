# Contributing to the Project

Thank you for your interest in contributing to this project! We appreciate your help in making this project better. Please follow the steps below to get started.

## Setup Your Environment

### 1. Install Required Tools

Before you start, ensure you have the following tools installed:

- **setuptools**: A package development and distribution library.
- **wheel**: A built-package format for Python.
- **twine**: A utility for publishing Python packages on PyPI.


### 2. Install these tools by running the following command:
	pip install setuptools wheel twine

### 3. Building the Package
	python setup.py sdist bdist_wheel


### 4. Publishing to PyPI
Once you have an account on PyPI, you can upload the package by running the following command:

    twine upload dist/*
	