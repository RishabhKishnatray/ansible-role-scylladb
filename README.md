scylladb
=========

An Ansible role that installs scylladb cluster / Node.

Requirements
------------

None

Role Variables
--------------

See `defaults/main.yml` for the variables you can override. I will list them here in due course

Dependencies
------------

None

Example Playbook
----------------


```YAML
    - hosts: servers
      vars:
        seeds:
          - 10.0.10.2
          - 10.0.10.3
      roles:
         - samuelmwangiw.scylladb
```

License
-------

GPL
