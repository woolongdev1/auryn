
Debian
====================
This directory contains files used to package aurynd/auryn-qt
for Debian-based Linux systems. If you compile aurynd/auryn-qt yourself, there are some useful files here.

## auryn: URI support ##


auryn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install auryn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aurynqt binary to `/usr/bin`
and the `../../share/pixmaps/auryn128.png` to `/usr/share/pixmaps`

auryn-qt.protocol (KDE)

