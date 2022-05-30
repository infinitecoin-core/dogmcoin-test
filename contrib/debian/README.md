
Debian
====================
This directory contains files used to package dogmcoind/dogmcoin-qt
for Debian-based Linux systems. If you compile dogmcoind/dogmcoin-qt yourself, there are some useful files here.

## dogmcoin: URI support ##


dogmcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dogmcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dogmcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/dogmcoin128.png` to `/usr/share/pixmaps`

dogmcoin-qt.protocol (KDE)

