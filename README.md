# pluralistex

[![PyPI](https://img.shields.io/pypi/v/pluralistex.svg)](https://pypi.org/project/pluralistex/)
[![Changelog](https://img.shields.io/github/v/release/crossjam/pluralistex?include_prereleases&label=changelog)](https://github.com/crossjam/pluralistex/releases)
[![Tests](https://github.com/crossjam/pluralistex/workflows/Test/badge.svg)](https://github.com/crossjam/pluralistex/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/crossjam/pluralistex/blob/master/LICENSE)

Platform for prototypes around Pluralistic.net data captures

## Installation

Install this tool using `pip`:

    pip install pluralistex

## Usage

For help, run:

    pluralistex --help

You can also use:

    python -m pluralistex --help

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd pluralistex
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
