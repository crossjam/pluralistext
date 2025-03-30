# pluralistext

[![PyPI](https://img.shields.io/pypi/v/pluralistext.svg)](https://pypi.org/project/pluralistext/)
[![Changelog](https://img.shields.io/github/v/release/crossjam/pluralistext?include_prereleases&label=changelog)](https://github.com/crossjam/pluralistext/releases)
[![Tests](https://github.com/crossjam/pluralistext/workflows/Test/badge.svg)](https://github.com/crossjam/pluralistext/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/crossjam/pluralistext/blob/master/LICENSE)

Platform for prototypes around Pluralistic.net data captures

## Installation

Install this tool using `pip`:

    pip install pluralistext

## Usage

For help, run:

    pluralistext --help

You can also use:

    python -m pluralistext --help

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd pluralistext
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
