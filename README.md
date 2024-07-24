# ignition-copier-templates

ignition-devs [copier] templates for Ignition projects.

## Pre-requisites

- Git
- [Python 2.7.18] (for `jython-package` and `python2-package`)
- [Python 3.12]
- [copier]

  ```sh
    python3 -m pip install copier
  ```

## Templates

### ignition-project

- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [flake8]
  - [isort]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
- Tests run with [sourcery] and [tox]
- [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### jython-package

- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [flake8]
  - [isort]
  - [mypy]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
- Tests run with [sourcery], [tox] and [make]
- [Jython 2.7.3], [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### python2-package

- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [flake8]
  - [isort]
  - [mypy]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
- Tests run with [sourcery] and [tox]
- [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### python3-stubs

- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [flake8]
  - [isort]
  - [mypy]
- Tests run with [tox]
- Python 3.12
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

## Quick setup and usage

### Generating a project

You can generate a project from a template using the copier command-line tool:

```sh
copier copy gh:ignition-devs/ignition-copier-templates /path/to/destination
```

### Updating a project

Navigate to your project's directory, make sure git status shows it clean, and run:

```sh
copier update --defaults
```

<!-- Links -->
[copier]: https://copier.readthedocs.io/en/stable/
[Jython 2.7.3]: https://repo1.maven.org/maven2/org/python/jython-installer/2.7.3/
[Python 2.7.18]: https://www.python.org/downloads/release/python-2718/
[Python 3.12]: https://www.python.org/downloads/release/python-3214/
<!-- Tools -->
[black]: https://black.readthedocs.io/en/stable/
[docformatter]: https://docformatter.readthedocs.io/en/stable/
[flake8]: https://flake8.pycqa.org/en/5.0.4/
[isort]: https://pycqa.github.io/isort/
[make]: https://www.gnu.org/software/make/
[mypy]: https://coatl-mypy.readthedocs.io/en/v0.971/
[pydocstyle]: https://www.pydocstyle.org/en/6.3.0/
[pylint]: https://pylint.readthedocs.io/en/stable/
[sort-all]: https://github.com/aio-libs/sort-all
[sourcery]: https://docs.sourcery.ai/About-Sourcery/
[ssort]: https://github.com/bwhmather/ssort
[tox]: https://tox.wiki/
