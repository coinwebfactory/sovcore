
Debian
====================
This directory contains files used to package zsovd/zsov-qt
for Debian-based Linux systems. If you compile zsovd/zsov-qt yourself, there are some useful files here.

## zsov: URI support ##


zsov-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zsov-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zsovqt binary to `/usr/bin`
and the `../../share/pixmaps/zsov128.png` to `/usr/share/pixmaps`

zsov-qt.protocol (KDE)

