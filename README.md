Role Name
=========
This role install and configure specific wordpress version

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements.

Role Variables
--------------

You must change your db and user information from defaults/main.yml.
Also you can encrypt it with anisble-vault.


Example Playbook
----------------

```
---
- name: Install and Configure Wordpress
  hosts: all
  roles:
    - wordpress
```

