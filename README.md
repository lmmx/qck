# qck

[![Documentation](https://readthedocs.org/projects/qck/badge/?version=latest)](https://qck.readthedocs.io/en/latest/)
[![CI Status](https://github.com/lmmx/qck/actions/workflows/master.yml/badge.svg)](https://github.com/lmmx/qck/actions/workflows/master.yml)
[![Coverage](https://codecov.io/gh/lmmx/qck/branch/master/graph/badge.svg)](https://codecov.io/github/lmmx/qck)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Rubber ducking code with language models

[Read The Docs](https://qck.readthedocs.io/en/latest/)

## Idea

- Run language models on code to extract meaning (broadly defined)
- Run question generation models to deliberate unclear meaning
- Interpret docstrings to incorporate background knowledge into the above
- Run a 'loop' in which docstrings are added to code to make the meaning more interpretable
- Suggest better names for semantic placeholders (like `k, v` for key, value rather than what is in
  the dictionary)
- Suggest `typing.NewType` to distinguish plain types, and try to autogenerate data models of types

## Requires

- Python 3.9+

## Installation

```sh
pip install qck
```

> _qck_ is available from [PyPI](https://pypi.org/project/qck), and
> the code is on [GitHub](https://github.com/lmmx/qck)
