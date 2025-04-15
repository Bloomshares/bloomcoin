
Debian
====================
This directory contains files used to package bloomcoind/bloomcoin-qt
for Debian-based Linux systems. If you compile bloomcoind/bloomcoin-qt yourself, there are some useful files here.

## bloomcoin: URI support ##


bloomcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bloomcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bloomcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bloomcoin128.png` to `/usr/share/pixmaps`

bloomcoin-qt.protocol (KDE)

