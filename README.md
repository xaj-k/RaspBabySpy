# RaspBabySpy
Downloaded raspbian-lite from raspberrypi website
used laptop image writer to write .img to micro sd card (after unzipping the download)
followed quick start guide to boot up, tried manually connecting pi to wi-fi, but failed (should probably clear command history and delete /etc/wpa_supplicant.conf)
did:
sudo raspi-config
to start the config wizard where (under advanced settings) I enabled ssh, vnc and then after rebooting I did the unpack filesystem to be able to use the whole sd card (don't know if this works yet)
next step will be to configure router to statically assign raspberry pi ip address, then update packages, install zoneminder and configure
