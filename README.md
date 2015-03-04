Hostname
========

[![Build Status](https://api.travis-ci.org/azmelanar/ansible-hostname.png)](https://travis-ci.org/azmelanar/ansible-hostname) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-hostname-blue.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2592)

Role for manage hostname and hosts file.

Requirements
------------

Tested with Ansible 1.8.2

Role Variables
--------------

Default value can be found in defaults/main.yml

    hostname: localhost

Dependencies
------------

None

Example Playbook
----------------

Example of usage:

    - hosts: servers
      roles:
         - { role: azmelanar.hostname, hostname: server.example.com, hosts: { server1: 192.168.0.1, server2: 192.168.0.2 } }

License
-------

MIT

Feedback, improvements, bugs
----------------------------

Please use [issues](https://github.com/azmelanar/ansible-hostname/issues).
