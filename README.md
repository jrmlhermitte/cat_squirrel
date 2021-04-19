# Description
Test cat/squirrel classifier.


# Packaging
This repo uses [poetry](https://python-poetry.org/) 
for package management.
Package version contraints are listed 
in the `pyproject.toml` and 
explicit versions used generated in the `poetry.lock`.

The `requirements.txt` must be manually generated, 
if needed.

## Regenerate requirements
```bash
poetry export -r requirements.txt > requirements.txt
```

## Update package versions
```bash
poetry update
```
