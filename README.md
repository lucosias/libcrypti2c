# Cryptotronix libcrypti2c

[![Build Status](https://travis-ci.org/cryptotronix/libcrypti2c.png)](https://travis-ci.org/cryptotronix/libcrypti2c)

## About


`libcrypti2c` is a library for interfacing with embedded cryptographic devices on the I2C bus. It is a small collection of utility functions that handling:

- memory allocation (wrappers that zero out allocated memory)
- very basic logging
- i2c bus acquisition
- crc
- Guile extensions for interactive i2c programming (in progress).

It relies on [libgcrypt](https://www.gnu.org/software/libgcrypt/) for all cryptographic primitives.

# Supported Device

Currently the library is designed for the following devices:

- [Atmel ATSHA204](http://www.atmel.com/devices/atsha204.aspx)
- [Atmel ECC108](http://www.atmel.com/devices/atecc108.aspx)

# Status

This software is currently in ***ALPHA***. Expect numerous changes to the ABI.

# Post install

After installing, don't forget to run `ldconfig`.


![LGPLv3](https://www.gnu.org/graphics/lgplv3-147x51.png)
