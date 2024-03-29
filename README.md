# KArchUpdate
Script to handle many Arch Linux updates operations in one command line.

## How to use
To update your system with this script, simply type the following command:
```
$ k-arch-update
```
**Note that you shouldn't execute the script in root.**

If you have activated the AUR updates and want to prevent one or more AUR packages
to be updated, add the ".disabled" extension to the AUR package directory. For example,
you can rename "~/.aur/foobar" to "~/.aur/foobar.disabled".

## Configuration
The behavior of the script can be configured. To to this, copy the example configuration file
provided like this:
```
# cp /usr/share/k-arch-update/k-arch-update.conf.default /etc/k-arch-update.conf
```