
Debian
====================
This directory contains files used to package suprad/supra-qt
for Debian-based Linux systems. If you compile suprad/supra-qt yourself, there are some useful files here.

## supra: URI support ##


supra-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install supra-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your supraqt binary to `/usr/bin`
and the `../../share/pixmaps/supra128.png` to `/usr/share/pixmaps`

supra-qt.protocol (KDE)

