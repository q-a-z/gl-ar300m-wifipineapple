# gl-ar300m-wifipineapple
Wifi PIneapple for GL-AR300M


1. Flash stock firmware (openwrt-ar300m-clean-2.264.img) with uboot to nand
2. boot it
3. on "firmware upgrade" page use openwrt-ar71xx-nand-gl-ar300m-squashfs-sysupgrade.tar, set "keep settings" to NONE
4. wait
5. connect to web interface and setup your password
6. ssh root@172.16.42.1
7. connect to internet
8. do things


features:  


* libpcap 1.8.1  
* mana-toolkit (hostapd-mana, sslstrip2, dns2proxy, net-creds, firelamb (/usr/share/mana-toolkit/))  
* lot of usb wifi drivers (all available)  


bugs:  
* LAN and WAN interfaces are misplaced     
* python 2.7 not working correctly
