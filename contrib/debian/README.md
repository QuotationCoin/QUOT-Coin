
Debian
====================
This directory contains files used to package quotationd/quotation-qt
for Debian-based Linux systems. If you compile quotationd/quotation-qt yourself, there are some useful files here.

## quotation: URI support ##


quotation-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quotation-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quotationqt binary to `/usr/bin`
and the `../../share/pixmaps/quotation128.png` to `/usr/share/pixmaps`

quotation-qt.protocol (KDE)

