sudo ip link set wlan1 down
sudo iw dev wlan1 set type monitor
sudo ip link set wlan1 up


sudo bettercap -iface wlan1

wifi.recon on

