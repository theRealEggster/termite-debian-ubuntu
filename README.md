Termite build script for Ubuntu
=====

Termite terminal build and install script for Ubuntu.
It is based on the [terminal-install](https://github.com/Corwind/termite-install/blob/master/termite-install.sh) script,
but statically link [vte-ng](https://github.com/thestinger/vte-ng) so it does not break other vte based terminals.

Tested on Ubuntu 18.04, 19.10, 20.04, 20.10, 21.04 and on Debian 11.

## How to use

To build and install termite (the script use sudo when necessary):

```
git clone https://github.com/ls4154/termite-ubuntu.git
cd termite-ubuntu
./build.sh
```

To uninstall termite:

```
./uninstall.sh
```

Mad props to ls4154!I found this at his github here: https://github.com/ls4154/termite-ubuntu. Copying to own repo incase it get removed.
