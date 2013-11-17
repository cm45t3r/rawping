Rawping
=======
Wrapper for [Pierre Bourdon's](https://pypi.python.org/pypi/ping) python ping implementation. It simplifies `verbose_ping()` function by printing one RTT per line and no statistics, easing integration with other tools. Unix shell execution is enabled.

As rawping uses raw ICMP requests for a very fast response, you must have root privileges to use it.

Rawping is also part of [nec-tp](https://github.com/cm45t3r/nec-tp) and [nec-ping](https://github.com/cm45t3r/nec-ping) utilities.

Installing
----------
Copy or clone the project:
```bash
git clone https://github.com/cm45t3r/rawping.git
```

Run `./install` as root on a Unix shell to enable <b>command-line-access</b> feature. This is not required whether you are thinking of running from a Python shell.

Running
-------
<b>Command-line-access</b> feature allows rawping to be run on a Unix or Python shell as it follows:
```
rawping <host> <count> <timeout> <packet size>
```

- `host`: ip address or qualified network name.
- `count`: number of echo requests to send.
- `timeout`: delay in seconds when there is no answer.
- `packet size`: payload size in bytes.
