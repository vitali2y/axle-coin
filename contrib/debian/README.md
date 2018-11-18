
Debian
====================
This directory contains files used to package axled/axle-qt
for Debian-based Linux systems. If you compile axled/axle-qt yourself, there are some useful files here.

## axle: URI support ##


axle-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install axle-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your axleqt binary to `/usr/bin`
and the `../../share/pixmaps/axle128.png` to `/usr/share/pixmaps`

axle-qt.protocol (KDE)

