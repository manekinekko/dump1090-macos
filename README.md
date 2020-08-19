# dump1090-macos MacOS package

This is a port of [dump1090-fa](https://github.com/adsbxchange/dump1090-fa)
customized for MacOS

## Building under jessie

### Dependencies - bladeRF

You will need to get `libbladeRF` from Brew: `brew install bladeRF`

### Dependencies - rtlsdr

You will also need to get `rtlsdr` from Brew: `brew install rtlsdr`

## Building manually

You can probably just run "make" after installing the required dependencies.
Binaries are built in the source directory; you will need to arrange to
install them (and a method for starting them) yourself.

"make BLADERF=no" will disable bladeRF support and remove the dependency on
libbladeRF.

"make RTLSDR=no" will disable rtl-sdr support and remove the dependency on
librtlsdr.

## Usage

`./dump1090 --help`
