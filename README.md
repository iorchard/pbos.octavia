pbos.octavia
==============

Ansible role to install and setup Octavia LB as a Service.

Requirements
------------

This role requires Ansible 2.11 or higher.

This role supports:

  - Rocky Linux 8.x

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    hosts: servers
    roles:
      - {role: pbos.octavia, tags: octavia}

It is installed on the node in inventory group:

    [octavia]
    host-1
    host-2
    host-3

License
-------

  - Code released under [Apache License 2.0](LICENSE)
  - Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

  - Heechul Kim @iOrchard
      - <https://github.com/iorchard>

