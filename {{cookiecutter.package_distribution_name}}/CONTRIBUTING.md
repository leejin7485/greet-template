# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

```bash
python -m pip install -e .
```

## Run the tests

Run the following command:

```bash
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```

Expected output: `Hello, Hee!`

## Send a change

1. Create a new branch from `main`.
2. Commit your changes and push the branch.
3. Open a pull request against `main`.