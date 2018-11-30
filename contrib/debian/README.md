
Debian
====================
This directory contains files used to package caluracoind/caluracoin-qt
for Debian-based Linux systems. If you compile caluracoind/caluracoin-qt yourself, there are some useful files here.

## caluracoin: URI support ##


caluracoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install caluracoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your caluracoinqt binary to `/usr/bin`
and the `../../share/pixmaps/caluracoin128.png` to `/usr/share/pixmaps`

caluracoin-qt.protocol (KDE)

