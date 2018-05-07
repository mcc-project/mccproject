
Debian
====================
This directory contains files used to package mccd/mcc-qt
for Debian-based Linux systems. If you compile mccd/mcc-qt yourself, there are some useful files here.

## mcc: URI support ##


mcc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mcc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mccqt binary to `/usr/bin`
and the `../../share/pixmaps/mcc128.png` to `/usr/share/pixmaps`

mcc-qt.protocol (KDE)

