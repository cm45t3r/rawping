Rawping
=======
Wrapper for [Pierre Bourdon's](https://pypi.python.org/pypi/ping) python ping implementation. It simplifies `verbose_ping()` function by printing just one RTT per line without statistics, easing integration with other tools. In addition, shell execution is enabled.

Rawping is also part of [nec-tp](https://github.com/cm45t3r/nec-tp) and [nec-ping](https://github.com/cm45t3r/nec-ping) utilities.

Installing
----------
After clonning or copying the project, run `install` on a Unix shell enabling Command-line-access feature. This is not required whether you are thinking of running from a Python shell.

Running
-------
Command-line-access feature allows rawping to be run on a Unix or Python shell as it follows:
```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address or qualified network name.
- `count`: number of simultaneous requests.
- `timeout`: delay in seconds when no answer.
- `packet size`: payload size in bytes.
