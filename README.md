# Ansible install docker binary

Supports the following Operating Systems:

  -  CentOS 7
  -  RedHat 7
  -  Ubuntu 16.04+
  -  Debian8+

## Role Variables

| Variable         | Required | Default    | Comments          |
| ---------------- | -------- | ---------- | ----------------- |
| `docker_version` | No       | `19.03.15` | Docker CE version |

## Example Playbooks

```yaml
- hosts: dockerhosts
  remote_user: root

  roles:
    - install-docker-binary
```
