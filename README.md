# Ansible Role: Update Apt packages

An Ansible role to udpate apt packages. This is merely a wrapper around the apt module in order for it to be used in a playbook's sequenceof roles.

## Requirements

This role requires Ansible 1.2 or higher.

## Role variables

Ansible variables are listed below with their default values.

```
packages:
  - python
```

## Example playbook

```
---
- hosts: webservers
  roles:
  	- opichon.apr-update-packages
```

## License

MIT

