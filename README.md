# Description
Test cat/squirrel classifier.

Run on binder by clicking
[here](https://hub.gke2.mybinder.org/user/jrmlhermitte-cat_squirrel-jcygmny0/notebooks/cat_squirrel_classifier.ipynb).

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
