spk83.jupyter-r-deps
====================

[![CircleCI](https://circleci.com/gh/spk83/ansible-jupyter-r-deps/tree/master.svg?style=shield)](https://circleci.com/gh/spk83/ansible-jupyter-r-deps/tree/master)

Installs R deps to run jupyter notebook with r-irkernel

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
    - spk83.jupyter-r-deps
```

License
-------

MIT

Author Information
------------------

Vishal Shah vishal.shah@nyu.edu
