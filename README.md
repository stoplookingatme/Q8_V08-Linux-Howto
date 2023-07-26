# Q8_V08-Linux-Howto
How to get Linux booting on some sun5i devices - https://linux-sunxi.org/Q8

Most information derived from https://linux-sunxi.org/Manual_build_howto

**!!UNFINISHED, DO NOT USE!!**

>If you are lazy and don't want your own image, you can get my debian image at the releases tab - Login: root, Password: toor

## The easy way: (For Q8_V08 or similar boards only)
You will need: One MircoSD card (Perferably being UHS-I or better if you don't want a slow system), a linux machine, a device with an Allwinner A13 (Sun5i), 
1. Obtain a rootfs for the distro of your choice, (ex. Arch Linux ARM http://os.archlinuxarm.org/os/ArchLinuxARM-armv7-latest.tar.gz)
2. Obtain 


## The hard way: (Custom settings, for expirenced users)
You will need: A MicroSD card (Perferably being UHS-I or better if you don't want a slow system), a linux system with an arm build environment, 
1. Make a virtual machine in Qemu, with the platform being Virt and CPU model Cortex-A8
2. Provide your own rootfs or boot off of an .iso
3. Make 2 or 3 partitions, 3rd optional if you want swap
   First partition for boot, 100M
   Second partition for root
   Third for swap
4. 
