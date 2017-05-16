# haproxy-windows
haproxy for windows (it is very easier to transfer others server)

#### QuickStart(use quiet mode)

    haproxy.exe -f config.json -q

#### These 3 files is required for running

    haproxy.exe cyggcc_s-1.dll  cygwin1.dll

```
Usage : haproxy [-f <cfgfile>]* [ -vdVD ] [ -n <maxconn> ] [ -N <maxpconn> ]
        [ -p <pidfile> ] [ -m <max megs> ] [ -C <dir> ] [-- <cfgfile>*]
        -v displays version ; -vv shows known build options.
        -d enters debug mode ; -db only disables background mode.
        -dM[<byte>] poisons memory with <byte> (defaults to 0x50)
        -V enters verbose mode (disables quiet mode)
        -D goes daemon ; -C changes to <dir> before loading files.
        -q quiet mode : don't display messages
        -c check mode : only check config files and exit
        -n sets the maximum total # of connections (2000)
        -m limits the usable amount of memory (in MB)
        -N sets the default, per-proxy maximum # of connections (2000)
        -L set local peer name (default to hostname)
        -p writes pids of all children to this file
        -de disables epoll() usage even when available
        -dp disables poll() usage even when available
        -dS disables splice usage (broken on old kernels)
        -dV disables SSL verify on servers side
        -sf/-st [pid ]* finishes/terminates old pids.
```
