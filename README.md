# OpenCore (0.8.8) EFI for Thinkpad T430 (macOS Monterey)

##### Specifications:

**CPU:** Intel Core i5-3320M  
**Wi-Fi:** Intel Centrino Advanced-N 6205  
**Bluetooth:** None  
**Audio:** Realtek ALC269 (layout-id 23)  
**Ethernet:** Intel 82579LM Gigabit Ethernet  
**Touchpad:** Synaptics PS/2 Trackpad  

##### SSDTs used:

**SSDT-BKEY** - brightness keys patch. might not work on your system, use SSDT-NBCF and BrightnessKeys.kext in that case  
**SSDT-ECRW** - patch for YogaSMC to work  
**SSDT-HPET** - fix HPET conflicts  
**SSDT-PM** - power management, **ONLY FOR I5-3320M!!!**  
**SSDT-PNLF** - display backlight control  
**SSDT-PRW0** - fix instant wake  
**SSDT-PTSWAKTTS-EXT3** - fix screen wake after sleep  
**SSDT-ThinkPad_TrackPad** - make the trackpad work correctly  
**SSDT-XOSI**
