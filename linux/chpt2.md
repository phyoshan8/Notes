# Linux basic and system configuration

power on > bios > Master Boot Record >  boot loader (grub)> kernel

-MBR:(512mb) 1st sector of the hard disk
-boot loader is stored in MBR:  LOAD THE KERNEL IMAGE, initial ram disk, file system to memory;

-initial ram disk fs:programs for mounting root fs

linux kernel: initialize ram, confg all the hardware connected to system,
--> run sbin/init : keeping ths sys run and shut down

systemd: multiple services simultaneously
/sbin/init --> lib/systemd/systemd

-systemctl  start,stop,run services
-fs: method of storing,finding files,
  -conventional
  -flash strg
  -db 
  -special purpose

-partition: section of a disc