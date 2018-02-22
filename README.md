Ansible Role: munin-node(pkg)
================================================================================
Install munin-node from package(rpm)

- Install munin-node

Requirements
--------------------------------------------------------------------------------
None

Role Variables
--------------------------------------------------------------------------------
These variables are defined in defaults/main.yml file.
```yaml
munin:
  node:
    started: True
    enabled: True
    rebuild: False
    workingdir: /usr/local/src
...
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - { role: azumakuniyuki.ar-munin-node-pkg }
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](https://nyaan.jp)

