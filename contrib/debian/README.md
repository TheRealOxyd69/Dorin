
Debian
====================
This directory contains files used to package dorind/dorin-qt
for Debian-based Linux systems. If you compile dorind/dorin-qt yourself, there are some useful files here.

## dorin: URI support ##


dorin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dorin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dorinqt binary to `/usr/bin`
and the `../../share/pixmaps/dorin128.png` to `/usr/share/pixmaps`

dorin-qt.protocol (KDE)

