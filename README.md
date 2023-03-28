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
<h6>Note: Some links may be offsite.</h6>
<br>
<h2>cd140201.zip</h2> (~18MB) - Bootable CD image. (md5sum: f274127bf8be9a7ed48b563fd951ae9e) - https://pogostick.net/~pnh/ntpasswd/cd140201.zip  <br>
<h2>usb140201.zip</h2> (~18MB) - Files for USB install (md5sum: a60dbb91016d93ec5f11e64650394afb) - https://pogostick.net/~pnh/ntpasswd/usb140201.zip <br>
