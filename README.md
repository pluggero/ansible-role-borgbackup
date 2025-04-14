# Ansible Role: borgbackup

[![CI](https://github.com/pluggero/ansible-role-borgbackup/actions/workflows/ci.yml/badge.svg)](https://github.com/pluggero/ansible-role-borgbackup/actions/workflows/ci.yml) [![Ansible Galaxy downloads](https://img.shields.io/ansible/role/d/pluggero/borgbackup?label=Galaxy%20downloads&logo=ansible&color=%23096598)](https://galaxy.ansible.com/ui/standalone/roles/pluggero/borgbackup)

An Ansible Role that installs a basic configuration of borgbackup.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
borg_backup_device: "sda"
borg_backup_device_id_serial_short: ""
```

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  roles:
    - pluggero.borgbackup
```

## License

MIT / BSD

## Author Information

This role was created in 2025 by Robin Plugge.
