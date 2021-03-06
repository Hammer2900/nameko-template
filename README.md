## Overview

Template for creating microservices in python using [nameko](https://www.nameko.io/).

## Usage

Prerequisite:

- [cookiecutter](https://github.com/cookiecutter/cookiecutter)
- [pipenv](https://github.com/pypa/pipenv)

To start new project:

```
cookiecutter gh:pythonjokeun/nameko-template
```

## Anatomy

- `src/` contains the service logic.
- `test/` contains code used for unit testing using `pytest`.
- `config/` contains configuration files used to run the service.
- `.env` contains environment variables during development.
