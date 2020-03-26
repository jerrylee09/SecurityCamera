# SecurityCamera

https://github.com/ccrisan/motioneyeos/releases
Download image from link

https://www.sdcard.org/downloads/formatter/
Download - formatting sd card

https://www.balena.io/etcher/
Download - Flash motioneyeos image into the sd card

Added network and and password in the wpa_supplicant.conf

Copy andPaste wpa_supplicant.conf into the flash sd card

Insert sd into Raspberrypi and start it up

Find your Ipaddress
ifconfig
    Look for 
        en0:
        this is your ipaddress - inet 192.168.1.XX 
    
Find device on your network use command 
sudo nmap -sP "ipaddress"/24

Find the device ip and copy and paste into your browser

username is admin. Password does not exist/ do not fill. Press enter.

