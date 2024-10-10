# How to change hidden bios variables to allow this EFI to work.

### WARNING ONLY DO THIS IF YOU HAVE A DELL Optiplex 7050!!

Update your bios to the latest version first.

Change your Sata type to AHCI not RAID

Next download this [EFI Shell](https://github.com/lukeshondas/Dell-Latitude-5290-Opencore/blob/main/EFI%20Shell.zip), extract the zip and copy the boot folder inside your EFI folder on a fat32 partition or USB. 
OR you may boot this EFI and when at the selection screen hit "Space" and select Modify UEFI

Once booted into the shell youll need to enter the following command's

`setup_var 0x4ED 0x00`

`setup_var 0x795 0x02`

`setup_var 0x796 0x03`

`setup_var 0x527 0x00`

Then type `exit` and reboot your PC

You can now use this EFI.

