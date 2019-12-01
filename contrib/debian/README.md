
Debian
====================
This directory contains files used to package itnd/itn-qt
for Debian-based Linux systems. If you compile itnd/itn-qt yourself, there are some useful files here.

## itn: URI support ##


itn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install itn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your itnqt binary to `/usr/bin`
and the `../../share/pixmaps/itn128.png` to `/usr/share/pixmaps`

itn-qt.protocol (KDE)

