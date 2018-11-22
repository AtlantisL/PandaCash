
Debian
====================
This directory contains files used to package pandacashd/pandacash-qt
for Debian-based Linux systems. If you compile pandacashd/pandacash-qt yourself, there are some useful files here.

## pandacash: URI support ##


pandacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pandacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pandacashqt binary to `/usr/bin`
and the `../../share/pixmaps/pandacash128.png` to `/usr/share/pixmaps`

pandacash-qt.protocol (KDE)

