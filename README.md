# python-project-template

Template Repo for Python Projects

## Usage

A new repo can be [initialised from this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)

You should then customise the following files for your project:

- `README.md`
- `pyproject.toml`

## Developers

Dependencies can be installed with [poetry](https://python-poetry.org/) by running

```bash
poetry install
```

### Pre-Commit Hooks

Pre commit hooks can be installed by running

```bash
pre-commit install
```

Pre-commit checks can then be run using

```bash
task lint
```

### Tests

Tests can be run with

```bash
task test
```
