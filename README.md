# sbts-boot-from-SSD
One command installation of boot from SSD for Jetson nano, Xavier NX and Xavier AGX

Simply clone this repo. Change into the clone and run:

sudo ./sbts_install_boot_from_SSD.sh

The system will wipe the SSD that you choose, create a partition the full size of the disk, copy
the SD disk to the new partion, change the boot sequence.

Once rebooted you will have booted from SSD. The approach taken here avoids the problem that existed
at the time of writing whereby the Jetson Xavier AGX won't boot from SSD without addition steps involving
some flashing.
