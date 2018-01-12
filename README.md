Ansible Role: Docker Install
=========

Install Docker on Linux.

Requirements
------------

None.

Role Variables
--------------

`docker_version`: The version of docker. (default: latest)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: djx339.docker-install, docker_version: latest }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
