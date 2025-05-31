# My Project Documentation

This repository contains the documentation for My Project, built using Sphinx and hosted on ReadTheDocs.

## Building the Documentation

To build the documentation locally:

1. Install Python dependencies:
   ```bash
   pip install -r docs/requirements.txt
   ```

2. Build the documentation:
   ```bash
   cd docs
   make html
   ```

3. View the documentation:
   The built documentation will be in `docs/_build/html/`

## Documentation Structure

- `docs/`: Contains all documentation source files
- `docs/conf.py`: Sphinx configuration
- `docs/index.rst`: Documentation homepage
- `.readthedocs.yml`: ReadTheDocs build configuration