
Debian
====================
This directory contains files used to package stemmad/stemma-qt
for Debian-based Linux systems. If you compile stemmad/stemma-qt yourself, there are some useful files here.

## stemma: URI support ##


stemma-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stemma-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stemmaqt binary to `/usr/bin`
and the `../../share/pixmaps/stemma128.png` to `/usr/share/pixmaps`

stemma-qt.protocol (KDE)

