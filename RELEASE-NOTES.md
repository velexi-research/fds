FastDS Release Notes
===============================================================================

-------------------------------------------------------------------------------
0.6.3 (2024-06-30)
==================
**Developer Updates:**
- Disabled `python-publish` GitHub Actions workflow.

-------------------------------------------------------------------------------
0.6.2 (2024-06-30)
==================
**Bug Fixes:**
- Fixed broken `fds` and `sdf` script installation.

**Developer Updates:**
- Added `[tool.poetry.scripts]` section to `pyproject.toml`.
- Added `fds` and `sdf` executables for use during development.
- Updated Makefile to use `lint` target to run flake8 checks during unit tests.
- Updated package dependencies.
  - Removed pytest-flake8 dependency.
- Updated unit tests to be compatible with recent versions of Python.
- Updated CI workflow.
  - Used `poetry` to install dependencies and run tests.
  - Improved robustness of lint task.

-------------------------------------------------------------------------------
