# Contributing to Roadmap Canary

Thank you for your interest in contributing! This document explains how to get started.

## Development Setup

```bash
git clone https://github.com/Farzine/roadmap-canary.git
cd roadmap-canary

python -m venv .venv
source .venv/bin/activate
pip install -e '.[dev]'
```

## Running Tests

```bash
pytest
```

## Code Style

- Follow PEP 8 conventions.
- Use type hints consistently.
- Keep modules small and focused.

## Pull Requests

1. Fork the repository and create a feature branch.
2. Write tests for new functionality.
3. Ensure `pytest` passes.
4. Submit a pull request with a clear description.

## Reporting Issues

Open an issue on GitHub with:
- A clear title and description.
- Steps to reproduce (if applicable).
- Expected vs actual behavior.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
