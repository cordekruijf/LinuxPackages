# Installation
```
ansible-playbook packages_playbook.yaml
```

## TODO:
- Mount HDD in /hdd
- Configure Apache

### Add .local/bin to PATH
Append to ~/.bashrc
```
export PATH="$HOME/.local/bin:$PATH"
```

Reload bash
```
source ~/.bashrc
```

### Curl install
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

## Add packages:
- vagrant
- unbound/NSD
- tor
- tcpdump
- tar
- rtl-sdr
- python
- openssl
- nmap
- netcat
- nftables # remove iptables/ufw
- mysql
- libreoffice
- iw
- httpd
- ewftools
- virtualbox
- flameshot
- JADX
- Ghidra
- Gqrx
