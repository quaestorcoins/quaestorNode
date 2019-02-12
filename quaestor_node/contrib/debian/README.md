
Debian
====================
This directory contains files used to package quaestord/quaestor-qt
for Debian-based Linux systems. If you compile quaestord/quaestor-qt yourself, there are some useful files here.

## quaestor: URI support ##


quaestor-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quaestor-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quaestor-qt binary to `/usr/bin`
and the `../../share/pixmaps/quaestor128.png` to `/usr/share/pixmaps`

quaestor-qt.protocol (KDE)

