# Ansible Role: Update Apt packages

An Ansible role to update apt packages. The aptitude package is always installed. In addition the role will perform an apt-upgrade.

## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
apt_upgrade: safe
packages:
  - python
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- opichon.apt-update-packages
```

## License

MIT
