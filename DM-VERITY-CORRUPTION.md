##Colocar aparelho no modo fastboot
- fastboot devices
- fastboot oem cdms fix
- fastboot reboot

## Se não funcionar execultar esse
- fastboot flash vbmeta --disable-verity --disable-verification vbmeta.img
