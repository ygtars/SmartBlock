
Debian
====================
This directory contains files used to package smartblockd/smartblock-qt
for Debian-based Linux systems. If you compile smartblockd/smartblock-qt yourself, there are some useful files here.

## smartblock: URI support ##


smartblock-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smartblock-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smartblockqt binary to `/usr/bin`
and the `../../share/pixmaps/smartblock128.png` to `/usr/share/pixmaps`

smartblock-qt.protocol (KDE)

