[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

gitlab
======

Installs and configures GitLab

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|----------------|---------|------------------------------|
| gitlab_version | 7.11.4  | Version of GitLab to install |

Dependencies
------------

None

Example Playbook
----------------

Install GitLab
```
- hosts: all
  roles:
    - { role: kbrebanov.gitlab }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
