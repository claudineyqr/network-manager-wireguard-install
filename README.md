# Network-Manager VPN Plugin for WireGuard Install/Uninstall

## Install wget

`sudo apt update && sudo apt install -y wget`

## Install Network-Manager VPN Plugin

`cd /tmp && wget -O install.sh https://raw.githubusercontent.com/claudineyqr/network-manager-wireguard-install/main/install.sh`

`chmod +x install.sh`

`sh ./install.sh`

## Uninstall Network-Manager VPN Plugin

`cd /tmp && wget -O uninstall.sh https://raw.githubusercontent.com/claudineyqr/network-manager-wireguard-install/main/uninstall.sh`

`chmod +x uninstall.sh`

`sh ./uninstall.sh`

After Uninstall reboot OS System
