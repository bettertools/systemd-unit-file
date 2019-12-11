# systemd-unit-file

Provides a way to modify systemd unit files on the command line.

Example: set an item in a systemd unit file:
```bash
$ systemd-unit-file set myunit.service Service 'ExecStart=echo hello'
```

This tool is not meant to modify the unit files for a running system, rather, it is meant to modify unit files for a package/rootfs that is being generated.

## Requirments

This tool requires python3.
