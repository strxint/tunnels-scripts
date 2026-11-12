
# ***Tunnels-scripts v4.0.0***

**-> Privacy and anonymity focused scripts for Linux <-**
**note: this scripts are included built-in in my custom private operating system based on Arch Linux(coming soon).**

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

## ***Installation***

Clone repo

```bash
  git clone https://github.com/strxint/tunnels-scripts
```

Get inside main folder

```bash
  cd tunnels-scripts
```

Ensure root and exec permissions

```bash
  command -v bash || echo “missing bash, install it”
  sudo chmod +x * || doas chmod +x *
```

Run any script as root

```bash
  sudo ./archnon || doas ./archnon
```

## ***License***
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) 
* [GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## ***Acknowledgements***

 - [Tor Project](https://www.torproject.org/)
 - [I2P - The Invisible Internet Protocol](https://i2p.net/en/)
 - [Bash - GNU Project](https://www.gnu.org/software/bash/)
 - [netfilter/iptables project](https://www.nftables.org/)
 - [curl](https://curl.se/)
