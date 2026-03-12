# Contributing to AgentSeek

Thank you for your interest in contributing to AgentSeek!

## How to Contribute

### Reporting Bugs

1. Search existing issues to avoid duplicates
2. Create a new issue with:
   - Clear title describing the bug
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details (OS, Python version, etc.)

### Feature Requests

1. Check existing feature requests
2. Open a new issue with:
   - Clear description of the feature
   - Use cases
   - Potential implementation approaches

### Pull Requests

1. Fork the repository
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes following the code style
4. Add tests if applicable
5. Commit and push:
   ```bash
   git add .
   git commit -m 'Add: Your feature description'
   git push origin your-branch-name
   ```
6. Open a Pull Request

## Development Setup

```bash
# Clone repository
git clone https://github.com/rawdripcollective-codec/agentseek.git
cd agentseek

# Install dependencies
pip install -r requirements.txt

# Run tests
pytest tests/
```

## Code Style

- Follow PEP 8 for Python code
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Comment complex logic

## Testing

```bash
# Run all tests
pytest

# Run specific test file
pytest tests/test_file.py

# Run with coverage
pytest --cov=. tests/
```

## Questions?

Open an issue for questions about contributing.

Thank you for contributing to AgentSeek!
