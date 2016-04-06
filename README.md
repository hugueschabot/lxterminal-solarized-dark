LXterminal is a VTE-based terminal emulator with support for multiple tabs.
It is completely desktop-independent and does not have any unnecessary
dependencies. In order to reduce memory usage and increase the performance
all instances of the terminal are sharing a single process.


# Solarized

This is a custom version of LXTerminal with the Dark Solarized Theme built-in.

See the [Solarized homepage](http://ethanschoonover.com/solarized) and the [Solarized repository](https://github.com/altercation/solarized) for more informations.


# Require dependencies (make)

## Arch Linux

    pacman -S base-devel docbook-xml

## Ubuntu

    apt-get install automake libgtk2.0-dev libvte-dev intltool xsltproc docbook-xml docbook-xsl

# Make & Install

    ./autogen.sh
    ./configure --enable-man
    make
    make install
