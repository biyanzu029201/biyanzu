
Debian
====================
This directory contains files used to package biyanzud/biyanzu-qt
for Debian-based Linux systems. If you compile biyanzud/biyanzu-qt yourself, there are some useful files here.

## biyanzu: URI support ##


biyanzu-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install biyanzu-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your biyanzu-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

biyanzu-qt.protocol (KDE)

