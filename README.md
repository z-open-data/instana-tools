## Installation
Requires Python3.8

### Dependencies
This package depends on `PyYaml`. Install using the Python package manager `pip install PyYAML`

## Usage
```
usage: python3.8 odp-instana-proxy [-h] --hostname HOSTNAME [--config CONFIG] --port PORT --target-hostname TARGET_HOSTNAME --target-port TARGET_PORT [--verbose]

ODP to Instana transformation proxy.

optional arguments:
  -h, --help            show this help message and exit
  --hostname HOSTNAME   The server hostname
  --config CONFIG       The config file name
  --port PORT           The server port
  --target-hostname TARGET_HOSTNAME
                        The target hostname
  --target-port TARGET_PORT
                        The target port
  --verbose             Print verbose output such as pretty printed JSON
```