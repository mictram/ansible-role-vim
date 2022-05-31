Role Name: Vim
=========

An Ansible role that installs and configures my personal Vim configuration.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```yml
# If 'true', skips building of of youcompleteme.
skip_ycm_build: false
```

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---
- hosts: localhost
  roles:
  - mictram.vim
```

License
-------

MIT

Author Information
------------------

This role was created in 2022 by Michael Ramos.
