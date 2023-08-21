# Ansible Role: dojo-exporter

This Ansible Role installs [dojo_exporter](https://github.com/bleetube/dojo_exporter).

Stuff todo: create on a separate user with a nologin shell.

## Requirements

None.

## Role Variables

None.

## Example Playbook

This role should not be run as root.

```yaml
- hosts: dojo-exporter
  roles:
    - role: bleetube.dojo-exporter
      tags: dojo-exporter
```
