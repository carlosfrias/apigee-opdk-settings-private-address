Apigee Settings Private Address
=========

This role will place the private IP address of an Apigee node in a variable named `private_address`.
The Ansible cache will be updated with `private_address` after this role is invoked.

Requirements
------------

N/A

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: apige-opkd-settings-private-address }

License
-------

Apache 2.0

Author Information
------------------

Carlos Frias