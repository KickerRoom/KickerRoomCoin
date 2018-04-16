
Debian
====================
This directory contains files used to package kickerroomd/kickerroom-qt
for Debian-based Linux systems. If you compile kickerroomd/kickerroom-qt yourself, there are some useful files here.

## kickerroom: URI support ##


kickerroom-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kickerroom-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kickerroom-qt binary to `/usr/bin`
and the `../../share/pixmaps/kickerroom128.png` to `/usr/share/pixmaps`

kickerroom-qt.protocol (KDE)

