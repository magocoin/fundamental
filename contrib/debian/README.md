
Debian
====================
This directory contains files used to package fundamentald/fundamental-qt
for Debian-based Linux systems. If you compile fundamentald/fundamental-qt yourself, there are some useful files here.

## fundamental: URI support ##


fundamental-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fundamental-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fundamentalqt binary to `/usr/bin`
and the `../../share/pixmaps/fundamental128.png` to `/usr/share/pixmaps`

fundamental-qt.protocol (KDE)

