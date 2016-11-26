# cloudshell_lcd
ODROID-XU4 Cloudshell LCD Informations for Server

<img src="doc/running.png" alt="hi" width="500"/>

A fork from the original repo for archlinux.

Differences from original package:
  - additional dependency: `bc`
  - removed font not on vanilla archlinux
  - LAN IP not working
  - added service to start at bootup (rather than a manual start of the script)

Installation:
    wget https://raw.githubusercontent.com/skilbjo/cloudshell-archlinux/master/src/cloudshell

    sudo ./cloudshell
