# python-example

Minimal Python repository used to validate Janitor behavior.

## Files

- `main.py`: small runnable program
- `pyproject.toml`: package metadata
- `.github/workflows/janitor.yml`: Janitor GitHub Actions workflow

## Run locally

```bash
python3 main.py
```

## Validate Janitor locally

From this directory, run:

```bash
janitor --no-commit
```

## CI behavior

`janitor.yml` runs on pushes and pull requests to `main` and executes Janitor in `no_commit` mode.
