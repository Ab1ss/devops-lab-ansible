# DevOps Lab Ansible

Ansible configuration for managing DevOps Lab virtual machines.

## Current inventory

- `inventories/lab` — laboratory infrastructure

## Test connectivity

```bash
ansible all -m ansible.builtin.ping
