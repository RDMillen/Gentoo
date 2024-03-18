# Gentoo

This is a personal repository containing config files for my Gentoo
installation with BSPWM, SXHKD and Polybar. Plus, being Gentoo, my make.conf
and Kernel configuration file for kernel version 6.1.46.

# Kernel
The kernelConfig file can be placed at /usr/src/linux/.config on T480 machines, minor chages to WiFi firmware loading required as of 6.6-21.
I have it setup to build with support for:
- Virtualised guest machines
- LUKS on LVM
- EXT4 root filesystem
- Support for IWD, Wireguard, NFS and CIFS/SMB
- Nvidia and Optimus support enabled
- Updated to include firmware for the Intel AX200 WiFi card

# Make.Conf
Some of the stuff that is defined here:
- Intel i7 8650U CPU Flags
- Nvidia MX150 GPU
- LUKS on LVM
- PipeWire Audio
- Build with en_GB localisation where available
- UEFI GRUB target
- The heretical ACCEPT_LICENSE="*"

# BSPWM, SXHKD, Polybar and Rofi
All these files are purely aesthic and application autostart on my machines. SXHKD is default apart from Alacritty terminal emulator, brightness and sound controls.
