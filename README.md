![Ansible Lint](https://github.com/johanneskastl/ansible-role-configure_net-snmp_agent/workflows/Ansible%20Lint/badge.svg)

configure_net-snmp_agent
=========

Configure and start the net-snmp agent with just a read-only user

Requirements
------------

None.

Role Variables
--------------

`snmp_password`: Password that should be set for the snmp user (for both authentication and privacy passphrase).

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.configure_net-snmp_agent', snmp_password: 'IamVeryVeryInsecure' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
