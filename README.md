# PyProject Template

Python project template

## Install

For running

```bash
conda create -n <YOUR_ENV_NAME> python=<YOUR_PYTHON_VERSION>
conda activate <YOUR_ENV_NAME>
pip install -e .
```

For development

```bash
conda create -n <YOUR_ENV_NAME> python=<YOUR_PYTHON_VERSION>
conda activate <YOUR_ENV_NAME>
pip install -e ".[dev]"
```

## Linting & Formatting Tools

- black
- ruff
- pre-commit-hooks

## Testing Tools

- pytest

## Project Configuration Files

- .pre-commit-config.yaml
- pyproject.toml
- .github/workflows/ci.yml
