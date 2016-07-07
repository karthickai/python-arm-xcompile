python-arm-xcompile
===================

This is a build script for cross-compiling Python to target the ARM architecture.

You must have a cross-compile toolchain already set up (e.g. on Ubuntu run `sudo apt-get install gcc-arm-linux-gnueabihf`).

1. Edit `python_xcompile.sh` and change the variables at the top to match your environment.
2. Run `python_xcompile.sh`. This will download Python and build it for you.

Assuming the build succeeds, the Python distribution will be installed in `INSTALL_DIRECTORY`.

The script was tested with Python 2.7.12 under Ubuntu Xenial 16.04.

With Python 2.7.12 cross-compiling got easier since no patching is required.
For cross-compiling older Python version, check the python-2.7.5 branch of this repository.
