# winiso2usb
Create USB boot disk in Linux from Microsoft Windows Setup CD/DVD image

### Solution description:
1. partition and format the USB stick
2. copy all the files in iso image into the new partition
3. setup grub on the USB stick

###  Dependency:
* >=bash-4.0 use its buildin regexp and associative array
* coreutils use mktemp
* util-linux use blkid,fdisk
* p7zip extrace file from ISO
* cdrtools use isoinfo
* ntfs-3g format partition to ntfs
* >=grub-2.0
