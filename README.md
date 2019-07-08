andrewrothstein.devpiserver
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-devpiserver.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-devpiserver)

Installs a [devpi](https://devpi.net/docs/devpi/devpi/stable/%2Bd/index.html) server.

Requirements
------------

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
    - andrewrothstein.devpiserver
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
