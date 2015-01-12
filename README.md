Ansible playbook for Sphinxdoc dependencies
===========================================

This role installs sphinxdoc dependencies.

Requirements
------------

This role requires Ansible 1.4 or higher and platform requirements are listed
in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about
them are as follows.

```
sphinxdoc_install_rdt_theme: True
```

Examples
========

```
# Roles
- name: sphinxdoc builder
  hosts: sphinxdoc
  user: root
  roles:
    - sphinxdoc

```

Dependencies
------------

None

License
-------

GPL

Author Information
------------------

Pierre Mavro / deimosfr


