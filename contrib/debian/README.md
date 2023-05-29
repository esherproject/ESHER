
Debian
====================
This directory contains files used to package esherd/esher-qt
for Debian-based Linux systems. If you compile esherd/esher-qt yourself, there are some useful files here.

## pivx: URI support ##


esher-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install esher-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your esher-qt binary to `/usr/bin`
and the `../../share/pixmaps/esher128.png` to `/usr/share/pixmaps`

esher-qt.protocol (KDE)

