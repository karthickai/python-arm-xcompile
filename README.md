python-arm-xcompile
===================

This is a build script and patches for cross-compiling Python to target the ARM architecture.

You must have a cross-compile toolchain already set up (e.g. on Ubuntu run `sudo apt-get install gcc-arm-linux-gnueabihf`).

1. Edit `python_xcompile.sh` and change the variables at the top to match your environment.
2. Run `python_xcompile.sh`. This will download Python and build it for you.

Assuming the build succeeds, the Python distribution will be installed in `INSTALL_DIRECTORY`.

Credits
-------

* Forked from [sjkingo/python-arm-xcompile](https://github.com/sjkingo/python-arm-xcompile).
* The `files/Python-2.7.5-xcompile.patch` file is from the patch given by
Trevor Bowen on the Python bug tracker [issue19142](http://bugs.python.org/issue19142).
