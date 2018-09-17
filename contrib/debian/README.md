
Debian
====================
This directory contains files used to package marcod/marco-qt
for Debian-based Linux systems. If you compile marcod/marco-qt yourself, there are some useful files here.

## marco: URI support ##


marco-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install marco-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your marcoqt binary to `/usr/bin`
and the `../../share/pixmaps/marco128.png` to `/usr/share/pixmaps`

marco-qt.protocol (KDE)

