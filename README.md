Rawping
=======
Wrapper for [Pierre Bourdon's](https://pypi.python.org/pypi/ping) python ping implementation. It simplifies `verbose_ping()` printing one RTT by line and no statistics as well as enabling command line execution.

Installing
----------
After clonning, run `install` on a unix shell.

Running
-------
Command-line-enabled feature allows rawping to be run directly:
```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address or qualified network name.
- `count`: number of simultaneous requests.
- `timeout`: delay in seconds when no answer.
- `packet size`: payload size in bytes.
