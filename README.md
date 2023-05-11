# Ansible Role: HTTPD Server STIG

![CI](https://github.com/acavella/ansible-role-httpdserverstig/actions/workflows/ci.yml/badge.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/acavella/ansible-role-httpdserverstig)
![GitHub repo size](https://img.shields.io/github/repo-size/acavella/ansible-role-httpdserverstig)

An Ansible Role to apply the latest server STIG to Apche HTTPd on Enterprise Linux.

## Requirements

| Name | Version | Notes |
| ----- | ----- | ----- |
| Red Hat Enterprise Linux | 7,8,9 | NA |
| Apache HTTPd | 2.4.x | NA |
| Ansible-Core | 2.9+ | NA |

## Role Variables

All available variables are found in `defaults/main.yml`.  I checklist item can be turned off by setting the "Manage" variable to False.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - { role: acavella.httpdserverstig }
```
## License

GNU General Public License v3.0

## Author Information

This role was created in 2023 by [Tony Cavella](https://www.cavella.com/)
