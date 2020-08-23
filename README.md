Role Name
=========

An Ansible role for installing FLASH2 in a Conda environment. 

Requirements
------------

This module uses The BioLighthouse Conda module.

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: tannerdowhy.flash2
```

License
-------

BSD

Author Information
------------------

Tanner Dowhy <t.dowhy@usask.ca>
