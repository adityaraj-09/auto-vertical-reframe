# Contributing

Thanks for your interest in improving Verthor.

## Workflow

1. Fork the repository and create a feature branch off `main`.
2. Set up a local environment:
   ```bash
   python3 -m venv .venv && source .venv/bin/activate
   pip install -e .
   ```
3. Make your changes in a focused commit or small series of commits.
4. Run the linters locally before opening a PR:
   ```bash
   ruff check src
   black --check src
   ```
5. Open a pull request describing the motivation, the change, and any new CLI flags or defaults.

## Commit messages

Use short, imperative subjects (e.g. `fix: clamp zoom when mask area is tiny`). Conventional-style prefixes (`feat:`, `fix:`, `refactor:`, `docs:`) are preferred.

## Code style

- Python 3.11+, 88-column lines (Black + Ruff configured in `pyproject.toml`).
- Prefer dataclasses over ad-hoc tuples for structured state.
- Add a short comment only when the *why* is non-obvious.

## Reporting issues

Please include: input resolution and duration, the exact command you ran, the preset, and the log output with `--log-level DEBUG`.
