# Rawping

Rawping is a command-line tool to send lightweight fast ICMP echo probes. It wraps [Pierre Bourdon's](https://pypi.python.org/pypi/ping) ping implementation in python. It extracts RTTs from `verbose_ping()` and removes statistics.

Rawping allows to set the number of echos, timeout and packet size for each request.

## Installation

To clone the project, run:

```bash
git clone https://github.com/cm45t3r/rawping.git
```

To install the most recent release, run:

```bash
sudo ./install
```

## Running the tool

To do a ping request, run:

```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address, domain or qualified network name.
- `count`: number of echo probes to send. Minimum is 1.
- `timeout`: no reply time wait in seconds. Minimum is 1.
- `packet size`: payload size in bytes. Minimum is 1.

## Example

```bash
$ sudo rawping www.google.com 3 10 1
63.5860 ms
63.9200 ms
68.4309 ms
```

## Contributing

You are welcome to contribute to this tool creating issues and pull requests.

## Licence

This project is licensed under the MIT license. See the [LICENSE](https://github.com/cm45t3r/rawping/raw/master/LICENSE) file for more info.
