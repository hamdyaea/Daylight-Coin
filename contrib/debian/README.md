
Debian
====================
This directory contains files used to package daylightd/daylight-qt
for Debian-based Linux systems. If you compile daylightd/daylight-qt yourself, there are some useful files here.

## daylight: URI support ##


daylight-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install daylight-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your daylight-qt binary to `/usr/bin`
and the `../../share/pixmaps/daylight128.png` to `/usr/share/pixmaps`

daylight-qt.protocol (KDE)

