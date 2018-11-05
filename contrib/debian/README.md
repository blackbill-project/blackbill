
Debian
====================
This directory contains files used to package blackbilld/blackbill-qt
for Debian-based Linux systems. If you compile blackbilld/blackbill-qt yourself, there are some useful files here.

## blackbill: URI support ##


blackbill-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blackbill-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blackbillqt binary to `/usr/bin`
and the `../../share/pixmaps/blackbill128.png` to `/usr/share/pixmaps`

blackbill-qt.protocol (KDE)

