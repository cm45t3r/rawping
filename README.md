Rawping
=======
Wrapper for [Pierre Bourdon's](https://pypi.python.org/pypi/ping) python ping implementation. It simplifies `verbose_ping()` function by printing one RTT per line without statistics, easing integration among tools. In addition, shell execution is enabled.

Rawping is also part of [nec-ping](https://github.com/cm45t3r/nec-ping) utilities.

Installing
----------
After clonning, run `install` on a unix shell.

Running
-------
Command-line-enabled feature allows rawping to be run on a unix shell:
```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address or qualified network name.
- `count`: number of simultaneous requests.
- `timeout`: delay in seconds when no answer.
- `packet size`: payload size in bytes.
