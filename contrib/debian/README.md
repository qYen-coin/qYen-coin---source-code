
Debian
====================
This directory contains files used to package qyend/qyen-qt
for Debian-based Linux systems. If you compile qyend/qyen-qt yourself, there are some useful files here.

## qyen: URI support ##


qyen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qyen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qyen-qt binary to `/usr/bin`
and the `../../share/pixmaps/qyen128.png` to `/usr/share/pixmaps`

qyen-qt.protocol (KDE)

