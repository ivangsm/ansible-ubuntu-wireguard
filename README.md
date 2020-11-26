# Ansible Ubuntu Wireguard

This Ansible playbook installs and configures a WireGuard VPN server on `Ubuntu 20.04` and newer releases. 

Everything is configurable all you need to do is to modify the `vars` file & the `hosts` file.

## Requirements
This playbook tested on Ansible 2.9

## Installation
```sh
git clone https://git.io/Jk9EN
```

### Install from Ansible Galaxy
```sh
ansible-galaxy install ivangsm.ansible_ubuntu_wireguard
```

### Run Ansible playbook
```sh
ansible-playbook -i hosts_inventory wireguard.yml
```
## License
GPL v3.0
