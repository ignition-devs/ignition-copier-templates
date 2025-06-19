# ignition-copier-templates

ignition-devs [copier] templates for Ignition projects.

## Pre-requisites

- Git
- [Python 2.7.18] (for `jython-package` and `python2-package`)
- Python 3.12 (for [mypy])
- [copier]

  ```sh
    python3 -m pip install copier
  ```

## Templates

### ignition-project

- Automated code checks before committing to version control using [pre-commit]
- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [coatl-dev/flake8]
  - [isort]
  - [pydoclint]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
  - [unimport]
- Tests run with [sourcery] and [tox]
- [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### jython-package

- Automated code checks before committing to version control using [pre-commit]
- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [coatl-dev/flake8]
  - [isort]
  - [pydoclint]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
  - [unimport]
- Tests run with [sourcery], [tox] and [make]
- [Jython 2.7.3], [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### python2-package

- Automated code checks before committing to version control using [pre-commit]
- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [docformatter]
  - [coatl-dev/flake8]
  - [isort]
  - [pydoclint]
  - [pydocstyle]
  - [pylint]
  - [sort-all]
  - [ssort]
  - [unimport]
- Tests run with [sourcery] and [tox]
- [Python 2.7.18]
- Auto-generated `CHANGELOG.md` from git commits using [commitizen]

### python3-stubs

- Automated code checks before committing to version control using [pre-commit]
- Pre-configured tools for code formatting, quality analysis and testing:
  - [black]
  - [flake8]
  - [isort]
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
<!-- Tools -->
[black]: https://black.readthedocs.io/en/stable/
[coatl-dev/flake8]: https://flake8.pycqa.org/en/5.0.4/
[docformatter]: https://docformatter.readthedocs.io/en/stable/
[flake8]: https://flake8.pycqa.org/en/stable/
[isort]: https://pycqa.github.io/isort/
[make]: https://www.gnu.org/software/make/
[mypy]: https://coatl-mypy.readthedocs.io/en/v0.971/
[pre-commit]: https://pre-commit.com/
[pydoclint]: https://github.com/jsh9/pydoclint
[pydocstyle]: https://www.pydocstyle.org/en/6.3.0/
[pylint]: https://pylint.readthedocs.io/en/stable/
[sort-all]: https://github.com/aio-libs/sort-all
[sourcery]: https://docs.sourcery.ai/About-Sourcery/
[ssort]: https://github.com/bwhmather/ssort
[tox]: https://tox.wiki/
[unimport]: https://github.com/hakancelikdev/unimport
