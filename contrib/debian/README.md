
Debian
====================
This directory contains files used to package rupeecoind/rupeecoin-qt
for Debian-based Linux systems. If you compile rupeecoind/rupeecoin-qt yourself, there are some useful files here.

## rupeecoin: URI support ##


rupeecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rupeecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rupeecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/rupeecoin128.png` to `/usr/share/pixmaps`

rupeecoin-qt.protocol (KDE)

