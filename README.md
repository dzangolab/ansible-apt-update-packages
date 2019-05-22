# Ansible Role: Update Apt packages

An Ansible role to update apt packages. The aptitude package is always installed. In addition the role will perform an apt-upgrade.

## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
apt_upgrade: safe
packages:
  - ntp
  - python3-pip
  - sudo
  - unzip
pip_executable: pip3
pip_packages: []
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- dzangolab.apt-update-packages
```

## License

MIT
