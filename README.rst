===================
pabelanger.keystone
===================

Ansible role to manage Keystone

* License: Apache License, Version 2.0

Description
-----------

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

    - name: Install keysone
      hosts: keystone
      roles:
        - pabelanger.keystone
