
Debian
====================
This directory contains files used to package DudgXd/DudgX-qt
for Debian-based Linux systems. If you compile DudgXd/DudgX-qt yourself, there are some useful files here.

## DudgX: URI support ##


DudgX-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install DudgX-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your DudgXqt binary to `/usr/bin`
and the `../../share/pixmaps/DudgX128.png` to `/usr/share/pixmaps`

DudgX-qt.protocol (KDE)

