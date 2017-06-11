andrewrothstein.prometheus-alertmanager
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-prometheus-alertmanager.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-prometheus-alertmanager)

Installs the [Prometheus Alert Manager](https://github.com/prometheus/alertmanager)

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
    - andrewrothstein.prometheus-alertmanager
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
