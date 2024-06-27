# Bresser CCD driver

https://www.bresser.de

## Supported devices

Bresser USB 2.0 and USB 3.0 devices supported by vendor SDK. This driver supports only Breesser cameras and products produced by Touptek.

This driver supports hot-plug (multiple devices).

## Supported platforms

This driver depends on 3rd party library and is supported on Linux (Intel 32/64 bit, ARMHF and ARM64 bit) and MacOS.

## License

INDIGO Astronomy open-source license (3rd party library is closed source).

## Use

indigo_server indigo_ccd_bresser

## Status: Stable

## Driver is developed and tested with:

* Other Touptek OEM cameras

## Comments

There is a known issue with SDK and reopening the camera - exposure is not possible until the camera is reconnected.