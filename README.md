# Welcome to Kali-Linux

https://kali.training/topic/configuring-the-network/

### NETWORK
service wicd stop
service network-manager restart
ifconfig -a

/etc/network/hostname
invoke-rc.d hostname.sh start

/etc/network/interface
/etc/network/interfaces
/etc/init.d/networking-restart
service networking restart
update-rc.d networking enable
/etc/resolv.conf

Monitor Mode:
ifconfig wlan1 down
ifconfig wlan1 mode monitor
ifconfig wlan1 up
iwconfig

Wlan WPS check:
wash -i wlan1mon
reaver -i wlan1mon -c CHANNEL -b BSSID -v
(-d 5 = delay in Sekunden)

Re-install KaliLinux
apt-get install kali-linux-full -y

auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp


