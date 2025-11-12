# Vector Role

Ansible role for installing and configuring Vector log collector.

## Requirements

- Ubuntu 20.04/22.04
- Ansible 2.9+

## Role Variables

See `defaults/main.yml` for configurable variables.

## Example Playbook

```yaml
- hosts: all
  roles:
    - vector-role
