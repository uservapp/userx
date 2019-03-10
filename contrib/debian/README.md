
Debian
====================
This directory contains files used to package userxd/userx-qt
for Debian-based Linux systems. If you compile userxd/userx-qt yourself, there are some useful files here.

## userx: URI support ##


userx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install userx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your userxqt binary to `/usr/bin`
and the `../../share/pixmaps/userx128.png` to `/usr/share/pixmaps`

userx-qt.protocol (KDE)

