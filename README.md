Ansible Openresty Role 
=========

Offline install openresty

version: 1.19.3.1

------------
## Install role with ansible galaxy
```
ansible-galaxy role install wezhai.openresty
```

## Example Playbook
```
- name: Offline install openresty
  hosts: openresty_hosts
  gather_facts: false
  roles:
    - wezhai.openresty
```