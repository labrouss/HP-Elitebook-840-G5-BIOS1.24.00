# elitebook-840-g5 BIOS 01.24.00

OpenCore 0.9.2 configuration for a perfect vanilla installation on HP Elitebook 840 G5 

Credits go to MacWin21 by whome i was insired, files are also available at Github

Download ZIP and copy files under your EFI disk partition in /EFI/

# Currently verified and working in Monterey 10.16 :

- Trackpad I2C VoodooI2C and VoodooI2CHID (Trackpad preferences enabled and working as expected)
- Integrated LAN
- Battery indications, battery status OK
- Audio input/output and mic working
- Camera working
- Integrated iGPU working Intel 620
- USB all working
- Docking station working and docking station HDMI is working as dual monitor
- Sleep, Wake, WiFi working after wake
- Brightness control
- Volume control through keyboard
- NVME, Replaced non-working Samsung PM981 with Crusial P1
- Bluetooth (Installed a USB bluetooth dongle)


# Not Working / Not Tested :

- Handoff, iCloud, iMessage working 100%
- Fingerprint sensor (Not really tested)
- SD Card reader, tried Sinetek kext but couldnt make it to work
- HDMI Audio, not tested

# Dont forget to open config.plist and generate a new serial Macbook 15,4


