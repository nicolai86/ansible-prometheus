# prometheus ansible role

setup [prometheus](http://prometheus.io/)

## Usage

All you need to do is to include the role and customize your prometheus configuration file:

``` yml
---
- hosts: vm
  remote_user: vagrant
  sudo: true
  roles:
    - nicolai86.prometheus
```

This will setup the latest version of prometheus as a system service and start it as well.

See the example directory on how to customize the configuration.
