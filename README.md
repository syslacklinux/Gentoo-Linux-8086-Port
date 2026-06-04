<img width="205" height="59" alt="image" src="https://github.com/user-attachments/assets/db4101a3-8984-4e29-8c41-e1a40d50d6c9" /> <img width="250" height="167" alt="image" src="https://github.com/user-attachments/assets/301ac46e-a1dd-4e92-847d-87047eb0e07d" />

# Gentoo-Linux-8086-Port
This is a port of Gentoo to 8086 Based On ELKS

Installation

Build ELKS images On a modern Linux machine git clone https://github.com/jbruchon/elks.git cd elks make

Write floppy image

Insert a real floppy disk.

Use dd to write the image:

sudo dd if=elks.img of=/dev/fd0 bs=512

Boot hardware from floppy

Insert the floppy into your vintage PC.

Power on; ELKS should boot into its shell.

Login as root (no password).

Install to HDD

Partition the HDD using DOS tools or ELKS utilities.

Format with FAT or MINIX (mkfs.minix).

Copy ELKS system files from floppy to HDD.

Adjust boot sector or use a bootloader (ELKS includes simple boot code).

Reboot with HDD as primary boot device.

Login as root then vi /etc/issue then i Then Change ELKS 0.7.0 To This is gentoo linux 8086 edition

