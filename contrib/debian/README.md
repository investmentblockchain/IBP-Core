
Debian
====================
This directory contains files used to package icprod/icpro-qt
for Debian-based Linux systems. If you compile icprod/icpro-qt yourself, there are some useful files here.

## icpro: URI support ##


icpro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install icpro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your icpro-qt binary to `/usr/bin`
and the `../../share/pixmaps/icpro128.png` to `/usr/share/pixmaps`

icpro-qt.protocol (KDE)

