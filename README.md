**Disclaimer**: I am not responsible for what you do with this tool or this information. The use of this tool should only be attempted on networks you own or have permission to test. please use this tool wisely.

# MoeHacker (Termux)
MoeHacker is a Implementation of [oneshot](https://github.com/drygdryg/OneShot) on Termux with DEB package, is a WiFi Hacking tool that allows runs WPS PIN attacks ([Pixie Dust](https://forums.kali.org/showthread.php?24286-WPS-Pixie-Dust-Attack-Offline-WPS-Attack) and bruteforce) without monitor mode with the wpa_supplicant, Originally made by @rofl0r and modded by @drygdryg.

# Installation
```shell
apt install ./moe.deb
```

# DEB package build
```shell
make pack-deb
```

## Usage examples
Start Pixie Dust attack on a specified BSSID:
 ```shell
 sudo moe -i wlan0 -b 00:90:4C:C1:AC:21 -K
 ```
Show avaliable networks and start Pixie Dust attack on a specified network:
 ```shell
 sudo moe -i wlan0 -K
 ```
 
