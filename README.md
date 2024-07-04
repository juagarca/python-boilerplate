# Python Boilerplate

## Description

This is a python boilerplate that uses Poetry to manage the dependencies.

## Prerequisites

Make sure you have the following installed on your machine:

- [Python](https://www.python.org/downloads/) (>= 3.12)
- [Poetry](https://python-poetry.org/docs/#installation)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/juagarca/python-boilerplate.git
   cd yourproject
   ```

2. Install the dependencies:

```sh
poetry install
```

## Running Tests

To run tests using `pytest`:

```sh
poetry run pytest
```

## Code Style and Formatting

This project uses black, flake8, and isort for code formatting and linting.

### Formatting Code

To format the code using black:

```sh
poetry run black .
```

### Sorting Imports

To sort imports using isort:

```sh
poetry run isort .
```

### Linting Code

To lint the code using flake8:

```sh
poetry run flake8 .
```

## Directory Structure

```sh
python-boilerpate/
├── src/
│ └── __init__.py
│ └── main.py
├── tests/
│ └── __init__.py
│ └── test_main.py
├── .flake8
├── .gitignore
├── .python-version
├── poetry.lock
├── pyproject.toml
└── README.md
```
