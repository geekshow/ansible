# Ansible Inventory

This repository contains an Ansible inventory file (`inventory.ini`) that defines hosts for automation tasks.

## Inventory Groups

- **myhosts**:  
  - server  
  - server2

## Usage

To use this inventory with Ansible, specify the inventory file in your command:

```bash
ansible-playbook updates.ansible.yml -i inventory.ini --ask-become-pass
