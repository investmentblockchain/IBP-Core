
Debian
====================
This directory contains files used to package ibpd/ibp-qt
for Debian-based Linux systems. If you compile ibpd/ibp-qt yourself, there are some useful files here.

## ibp: URI support ##


ibp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ibp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ibp-qt binary to `/usr/bin`
and the `../../share/pixmaps/ibp128.png` to `/usr/share/pixmaps`

ibp-qt.protocol (KDE)

