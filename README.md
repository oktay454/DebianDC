# DebianDC
Domain Controller and Samba AD Graphic Interface Environment<br>
DebianDC provides a Domain Controller installation and graphical interface manage environment for Samba Active Directory.<br>
DebianDC installs a graphical interface called AD-Manager and manages the Active Directory environment with zenity screens.<br>

## Features
- Domain and Domain Controller setup
- User Management
- Group Management
- DNS Management (Samba Internal DNS)

## Requirements
desktop environment (mate, lxde etc.)<br>
*This work has been done on Debian distribution. (Debian9 stretch)<br>
Internal Samba DNS issues a problem in Debian Buster. Therefore, run with Debian 9.

## Installation and Usage
```sh
$ wget https://raw.githubusercontent.com/eesmer/DebianDC/master/debiandc-installer.sh
$ bash debiandc-installer.sh
```
Use DebianDC and AD-Manager with root user
#### DC Setup
Run the server-setup command from the terminal screen
```sh
$ server-setup
```
#### AD-Manager
Run the manager command from the terminal screen
```sh
$ manager
```
