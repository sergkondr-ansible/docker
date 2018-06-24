docker
=========

The role install docker and docker-compose(if you wish).

Role Variables
--------------
```
docker_version: "18.03.1"
docker_edition: "ce"
docker_release: "stable"

docker_install_compose: no
docker_compose_version: "1.21.2"
```

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: docker, docker_install_compose: yes }
```

License
-------

WTFPL

Author Information
------------------

[Sergey Kondrashov](https://github.com/sergkondr)