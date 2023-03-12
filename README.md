# eventhubs

[![PyPI](https://img.shields.io/pypi/v/eventhubs.svg)](https://pypi.org/project/eventhubs/)
[![Changelog](https://img.shields.io/github/v/release/zmoog/eventhubs?include_prereleases&label=changelog)](https://github.com/zmoog/eventhubs/releases)
[![Tests](https://github.com/zmoog/eventhubs/workflows/Test/badge.svg)](https://github.com/zmoog/eventhubs/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/zmoog/eventhubs/blob/master/LICENSE)

CLI tool to send and receive event data from Azure Event Hubs

## Installation

Install this tool using `pip`:

    pip install eventhubs

## Usage

For help, run:

    eventhubs --help

You can also use:

    python -m eventhubs --help

## Development

To contribute to this tool, first checkout the code. Then create a new virtual environment:

    cd eventhubs
    python -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
