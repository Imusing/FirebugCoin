
Debian
====================
This directory contains files used to package apterusd/apterus-qt
for Debian-based Linux systems. If you compile apterusd/apterus-qt yourself, there are some useful files here.

## lebowskiscoin: URI support ##


apterus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install apterus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your apterus-qt binary to `/usr/bin`
and the `../../share/pixmaps/lebowskiscoin128.png` to `/usr/share/pixmaps`

apterus-qt.protocol (KDE)

