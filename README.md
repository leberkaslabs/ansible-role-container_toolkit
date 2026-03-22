# Ansible Role: container_toolkit

[![Ansible Molecule](https://github.com/leberkaslabs/ansible-role-container_toolkit/actions/workflows/molecule.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-container_toolkit/actions/workflows/molecule.yml)

Install the NVIDIA Container Toolkit.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.container_toolkit
```

## License

Copyright (c) 2026 Niclas Spreng
