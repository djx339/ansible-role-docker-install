Ansible Role: Docker Install
=========

Install Docker on Linux.

Requirements
------------

None.

Role Variables
--------------

`docker_version`: The version of docker. (default: latest)
`docker_apt_repo`: The repo url for apt based system. (default: https://download.docker.com/linux/ubuntu)

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
