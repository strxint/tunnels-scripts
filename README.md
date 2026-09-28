
# ***Tunnels-scripts v4.0.0***

**-> Make Linux Truly anonymous and other stuff with some user-friendly scripts <-**
**note: this scripts are included builtin in my custom private operating system based in Arch Linux, see more info: https://github.com/strxint/tunnels-release**

## ***Features***

- Protocols: Tor, i2pd.
- Secure configuration: torrc, archnon.nft.
- Firewall: nftables.
- MACs script: saturn.
- Boot services: systemd, runit, open-rc.
- User friendly scripts.
- Easy to mount and use.
- 100% bash code.
- Dependencies handled by: apt, pacman, dnf, yum, apk, zypper, emerge, xbps-install.
- Anonymous DNS script: neptune.
- Support for custom Torrc: uranus.

## ***Authors***

- [@strxint](https://www.github.com/strxint) (archnon@protonmail.com)


## ***Extra***

- Firewall is root only, same with services.
- Scripts will not support s6 for boot services.
- Get my personal stuff like .zshrc, .shrc, here: https://github.com/strxint/tunnels-files

## ***Installation***

Clone repo

```bash
  git clone https://github.com/strxint/tunnels-scripts
```

Get inside folder

```bash
  cd tunnels-scripts
```

Ensure root and exec permissions

```bash
  sudo chmod +x * || doas chmod +x *
```

Run any script as root

```bash
  sudo ./archnon || doas ./archnon
```


## ***Preview & Demo***

![App Screenshot](https://github.com/strxint/tunnels-scripts/blob/main/demo.png)
![App Screenshot](https://github.com/strxint/tunnels-scripts/blob/main/demo1.png)
![App Screenshot](https://github.com/strxint/tunnels-scripts/blob/main/demo2.png)
![App Screenshot](https://github.com/strxint/tunnels-scripts/blob/main/demo3.png)

## ***License***
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) 
* [GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## ***Acknowledgements***

 - [Tor Project](https://www.torproject.org/)
 - [I2P - The Invisible Internet Protocol](https://i2p.net/en/)
 - [Bash - GNU Project](https://www.gnu.org/software/bash/)
 - [netfilter/iptables project](https://www.nftables.org/)
 - [curl](https://curl.se/)
