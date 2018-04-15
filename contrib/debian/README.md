
Debian
====================
This directory contains files used to package QQcoind/QQcoin-qt
for Debian-based Linux systems. If you compile QQcoind/QQcoin-qt yourself, there are some useful files here.

## QQcoin: URI support ##


QQcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install QQcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your QQcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/QQcoin128.png` to `/usr/share/pixmaps`

QQcoin-qt.protocol (KDE)

