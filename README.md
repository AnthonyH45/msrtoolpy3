# untested py3 port, used black formatter 
# https://github.com/psf/black

A linux tool for simple usage of the MSR605 magnet stripe reader/writer

USAGE:
```
    ./msrtool.py /dev/ttyUSB0
```

You should have write access to the serial port, so you either run this as
root or add yourself to the dialout group (or whatever group your linux
assigns /dev/ttyUSB0 to).

This is heavily based on the work from Damien Bobillot, who wrote the Python
driver for the MSR605's serial interface. I only wrapped a nicer frontend around.

As Damien's work is GPL, this is licensed under the terms of the GPL, too.
