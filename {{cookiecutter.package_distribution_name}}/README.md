# {{ cookiecutter.package_distribution_name }}

{{ cookiecutter.package_description }}

## Installation

```bash
python -m pip install -e .
```

## Use

```bash
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('world'))"
```