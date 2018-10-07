
Debian
====================
This directory contains files used to package skyhubd/skyhub-qt
for Debian-based Linux systems. If you compile skyhubd/skyhub-qt yourself, there are some useful files here.

## skyhub: URI support ##


skyhub-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install skyhub-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your skyhubqt binary to `/usr/bin`
and the `../../share/pixmaps/skyhub128.png` to `/usr/share/pixmaps`

skyhub-qt.protocol (KDE)

