rpi_swap
========
[![Ansible Lint](https://github.com/oxivanisher/role-rpi_swap/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-rpi_swap/actions/workflows/ansible-lint.yml)

Install and configure a `dphys-swapfile` on Raspberry Pi.

Role Variables
--------------

| Name            | Comment                               | Default value                    |
|-----------------|---------------------------------------|----------------------------------|
| rpi_swap_factor | The swap factor of the dphys swapfile | `2` |

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Swap file
  hosts: rpis
  roles:
    - role: oxivanisher.raspberry_pi.rpi_swap
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.raspberry_pi](https://galaxy.ansible.com/ui/repo/published/oxivanisher/raspberry_pi/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-raspberry_pi).
