## Installation Guide

```
git clone https://github.com/a5a5aa555oo/realtek_bluetooth_7.2rc1
```
```
cd realtek_bluetooth_7.2rc1
```
```
sudo dkms install $PWD
```

## Uninstallation Guide

```
sudo dkms remove btusb/7.2 --all
```
```
sudo rm -rf /usr/src/btusb-7.2
```
```
sudo rm /etc/modprobe.d/blacklist-btusb.conf
```
