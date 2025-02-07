# st - simple terminal

st is a simple terminal emulator for X which sucks less.

## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

``` bash
make clean install
```

## Applied patches

- st-anysize-20220718-baa9357.diff
- st-xresources-signal-reloading-20220407-ef05519.diff

## Running st

Refer to the man page.

