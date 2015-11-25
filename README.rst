================
ansible-role-ssh
================

Ansible role to manage SSH

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-ssh.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-ssh
* Bugs: https://bugs.launchpad.net/ansible-role-ssh

Description
-----------

Secure Shell is a cryptographic (encrypted) network protocol to allow remote
login and other network services to operate securely over an unsecured network.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install ssh
      hosts: ssh
      roles:
        - ansible-role-ssh
