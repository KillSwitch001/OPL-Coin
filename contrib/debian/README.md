
Debian
====================
This directory contains files used to package opld/opl-qt
for Debian-based Linux systems. If you compile opld/opl-qt yourself, there are some useful files here.

## opl: URI support ##


opl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install opl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your opl-qt binary to `/usr/bin`
and the `../../share/pixmaps/opl128.png` to `/usr/share/pixmaps`

opl-qt.protocol (KDE)

