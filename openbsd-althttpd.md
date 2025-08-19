Title: Running althttpd on OpenBSD
Tag: OpenBSD
Updated: $mdate

$tag

## Downloading and compiling althttpd

Download and extract sources from latest check-in:
[https://sqlite.org/althttpd/info/tip](https://sqlite.org/althttpd/info/tip)

Edit Makefile because there is -ldl in linking rule which is not
avaliable on OpenBSD and run:

```
$ make althttpsd
```

althttpsd is the binary with TLS support.  Copy binary into target
folder, I also rename it to althttpd for convenience.
..

## Setting up acme-client

..

## Running standalone

..

## Running with inetd

..

## Running with relayd
