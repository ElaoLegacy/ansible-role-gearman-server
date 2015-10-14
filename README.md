WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


Ansible Role - Gearman Server
===========================

A Gearman Server role to install Gearman Server on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Handlers
-------------

    gearman server restart  # Restart Gearman server


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.gearman-server }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
