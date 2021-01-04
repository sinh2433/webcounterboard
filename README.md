# webcounterboard

/etc/apt/source.list
deb http://ftp.kaist.ac.kr/raspbian/raspbian/ buster main contrib non-free rpi

/boot/config.txt
hdmi_force_hotplug=1

#한글설치
sudo apt-get install fonts-unfonts-core 

/boot/cmdline.txt
usbhid.mousepoll=0
