
Debian
====================
This directory contains files used to package xcientosd/xcientos-qt
for Debian-based Linux systems. If you compile xcientosd/xcientos-qt yourself, there are some useful files here.

## xcientos: URI support ##


xcientos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xcientos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xcientos-qt binary to `/usr/bin`
and the `../../share/pixmaps/xcientos128.png` to `/usr/share/pixmaps`

xcientos-qt.protocol (KDE)

