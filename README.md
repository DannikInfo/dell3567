# dell3567
EFI OpenCore for hackintosh (BigSur 11.1) on dell inspiron 3567 

## Hardware
- CPU: i3 6006U SKL  
- Graphic: intel hd graphics 520  
- RAM: 20GB  
- WiFi combo: DW1820A (default QCA9565, don't work)  

## info
- all work from efi kexts, but need fix camera, and don't work sd cards
- CPU in system info look like i5, if need change cpu type in config.plist in platformInfo
- may contain trash, but it work very good
- may have trouble with sleep
- need fix opencanopy, but i'm using apple type loading and don't contact with bootloader interface

## install
- in uefi set boot from USB efi, as a rule, uefi itself detects the bootloader on the USB
- restart PC and hold CMD(WIN)+V for start or CMD(WIN)+R or OPTION(ALT) for log in to boot menu
- if stuck try off in uefi wireless card
- install
- will be repeatedly(3 or 4) restarted but system will be installed and work