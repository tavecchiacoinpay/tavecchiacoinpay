
Debian
====================
This directory contains files used to package tavecchiacoinpayd/tavecchiacoinpay-qt
for Debian-based Linux systems. If you compile tavecchiacoinpayd/tavecchiacoinpay-qt yourself, there are some useful files here.

## tavecchiacoinpay: URI support ##


tavecchiacoinpay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tavecchiacoinpay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tavecchiacoinpay-qt binary to `/usr/bin`
and the `../../share/pixmaps/tavecchiacoinpay128.png` to `/usr/share/pixmaps`

tavecchiacoinpay-qt.protocol (KDE)

