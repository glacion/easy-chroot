# easy-chroot
Eliminates the need to manually perform mundane tasks when chrooting.

## What Does It Do
* Mounts /dev, /sys, /proc , /run and /sys/firmware/efi/efivars (if exists)
* Unmounts on exit.
* Sources the chroot's /etc/profile.
