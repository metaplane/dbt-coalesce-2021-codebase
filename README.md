# [Coalesce 2021] The Endpoints are the Beginning - Companion Code

This codebase contains a humble iPython notebook to start exploring the dbt Cloud and Metadata APIs. The notebook has a handful of utility functions to retrieve and manipulate results from those APIs, then visualize them in useful ways.

### Installing dependencies
This project uses Poetry to manage dependencies. To install Poetry, run `pip install poetry`. Then, running `poetry install` will install all dependencies. By default, poetry will create a virtual environment in a subfolder `.venv` in your project directory.

### Activate virtual environment
`source .venv/bin/activate`

### Enabling Jupyter extensions
For interactive widgets and network visualization, run the following commands in your terminal:
```
jupyter nbextension install --py ipycytoscape
jupyter nbextension enable --py ipycytoscape
```

### Starting notebook
Within the project root directory, run `jupyter lab` or `jupyter notebook` then open `dbt Coalesce Code.ipynb`. Once you enter in your dbt API key, you're ready to roll.