# Ansible install docker binary

Supports the following Operating Systems:

  -  CentOS 7+
  -  RedHat 7+
  -  Ubuntu 16.04+
  -  Debian8+

## Role Variables

| Variable         | Required | Default    | Comments          |
| ---------------- | -------- | ---------- | ----------------- |
| version          | Yes      | 19.03.15   | Docker CE version |
| x86_64_sha256    | Yes      | 5504d190eef37355231325c176686d51ade6e0cabe2da526d561a38d8611506f | sha256 file hash |

## Example Playbooks

```yaml
- hosts: dockerhosts
  remote_user: root

  roles:
    - install-docker-binary
```
