
Debian
====================
This directory contains files used to package marbled/marble-qt
for Debian-based Linux systems. If you compile marbled/marble-qt yourself, there are some useful files here.

## marble: URI support ##


marble-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install marble-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your marbleqt binary to `/usr/bin`
and the `../../share/pixmaps/marble128.png` to `/usr/share/pixmaps`

marble-qt.protocol (KDE)

