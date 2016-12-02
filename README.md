# Rawping

Rawping is a command-line tool for lightweight fast ICMP ping requests. It wraps [Pierre Bourdon's](https://pypi.python.org/pypi/ping) ping implementation for python. It simplifies `verbose_ping()` output, showing RTTs and removing statistics.

Rawping allows the user to customize number of echos to perform, timeout and packet size for each request.

## Installation

To clone the project, write:

```bash
git clone https://github.com/cm45t3r/rawping.git
```

To install the most recent release, run:

```bash
sudo ./install
```

## Running the tool

On a linux/unix shell, run:

```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address or qualified network name.
- `count`: number of echo requests to send.
- `timeout`: delay in seconds when there is no answer.
- `packet size`: payload size in bytes.

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

This project is licensed under the MIT license. See the [LICENSE](https://github.com/cm45t3r/rawping/blob/master/LICENCE) file for more info.