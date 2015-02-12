# c1_mali_ddx_poc
Proof of concept GE2D integration for the OdroidC1 X11 driver

The files here are intended to overwrite the c1_mali_ddx repo files int the ./src directory at https://github.com/mdrjr/c1_mali_ddx.

The resulting build shows the first steps in integrating GE2D hardware blit acceleration into a X11 driver for the OdroidC1.  Since the build is only of use to developers, only the files changed are included here.  This should hopefully discourage end users from building the driver with the expectation of a full featured working product.

TL;DR = This is not a working driver yet.  Its intended for developer experimentation only.
