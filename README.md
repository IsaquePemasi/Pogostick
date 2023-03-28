<h1>Forgot your Windows admin password?</h1>
Reinstall? Oh no... But not any more...
<h1>Overview</h1>
This is a utility to reset the password of any user that has a valid local account on your Windows system.
Supports all Windows from NT3.5 to Win8.1, also 64 bit and also the Server versions (like 2003, 2008, 2012)
You do not need to know the old password to set a new one.
It works offline, that is, you have to shutdown your computer and boot off a CD or USB disk to do the password reset.
Will detect and offer to unlock locked or disabled out user accounts!
There is also a registry editor and other registry utilities that works under linux/unix, and can be used for other things than password editing.
<h1>How it is done?</h1>
Windows stores its user information, including crypted versions of the passwords, in a file called 'sam', usually found in \windows\system32\config. This file is a part of the registry, in a binary format previously undocumented, and not easily accessible. But thanks to a German(?) named B.D, I've now made a program that understands the registry.
This site provides CD and floppy images for end users to easily edit their forgotten passwords. But it also provides full source code and binary builds of the tools to allow others to use as they like for other purposes. Registry format documentation also available.
<h1>Download</h1>
CD release, see below on how to use

cd140201.zip (~18MB) - Bootable CD image. (md5sum: f274127bf8be9a7ed48b563fd951ae9e)
usb140201.zip (~18MB) - Files for USB install (md5sum: a60dbb91016d93ec5f11e64650394afb)
The files inside the USB zip are exactly the same as on the CD. See below for instructions on how to make USB disk bootable.
Floppy release (not updated anymore), see below on how to use them

bd080526.zip (~1.4M) - Bootdisk image (md5sum: 37889e4c540504e59132bdcdfe7f9bb7)
drivers1-080526.zip (~310K) - Disk drivers (mostly PATA/SATA) (md5sum: 72ac1731c6ba735d0ac2746a30dbc3ee)
drivers2-080526.zip (~1.2M) - Disk drivers (mostly SCSI) (md5sum: 30172bec657c85a5f1a0b43601452fb7)
Previous versions may sometimes be found here (also my site)
NOTE: Versions before 0704xx will corrupt the disk on VISTA/win7/8!