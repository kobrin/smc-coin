
Debian
====================
This directory contains files used to package darknetd/smc-coin-qt
for Debian-based Linux systems. If you compile darknetd/smc-coin-qt yourself, there are some useful files here.

## smc-coin: URI support ##


smc-coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install smc-coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your smc-coin-qt binary to `/usr/bin`
and the `../../share/pixmaps/darknet128.png` to `/usr/share/pixmaps`

smc-coin-qt.protocol (KDE)

