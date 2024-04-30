# ansible-role-python
Ansible role for installing Python

# Supported Platforms
- RedHat 8
- RedHat 9

# Requirements
- The role supports the installation of Python versions `2.7`, `3.6`, `3.8`, `3.9`, `3.11` on EL8 and `3.9`, `3.11` on EL9. Default is `3.11`.

# Example Variables
```
python_version: "3.11"
python_install_headers: true
```

# Example Playbook
```
---
- hosts: all
  roles:
    - role: dborisov.python
```

# Role Variables
Please see `meta/argument_specs.yml`

# Dependencies
None

# License
MIT