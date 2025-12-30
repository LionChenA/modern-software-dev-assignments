# Assignments for CS146S: The Modern Software Developer

This is the home of the assignments for [CS146S: The Modern Software Developer](https://themodernsoftware.dev), taught at Stanford University fall 2025.

## Repo Setup
These steps work with Python 3.12.

1. Install uv (fast Python package manager)
   ```bash
   pip install uv
   ```

2. Create and activate a virtual environment with Python 3.12
   ```bash
   uv venv --python 3.12
   .venv\Scripts\activate
   ```

3. Install project dependencies
   From the repository root:
   ```bash
   uv pip install -e ".[dev]"
   ```