Notepadqq
=========

Dependencies
------------
   * QScintilla (libqscintilla2-11)
   * libmagic-dev

Bug Tracking
------------
To report any bug, use Launchpad: https://bugs.launchpad.net/notepadqq

How to build
------------
You can build and install Notepadqq from command line:

    notepadqq/src$ qmake-qt4 PREFIX=/usr/local notepadqq.pro -r -spec linux-g++
    notepadqq/src$ make
    notepadqq/src$ make install

You can also build a Debian package:

    notepadqq$ dpkg-buildpackage -b -us -uc
