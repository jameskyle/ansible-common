Role Name
=========

Performs tasks and provides handlers common to systems I configure.

Role Variables
--------------

mgmt_addr
    the address used as the main management interface for the machine.
    default: ansible_default_ipv4.address

dns1
    primary dns server.
    default: 8.8.8.8

hostname
    hostname for the server.
    default: host1

management_interface
    primary interface for server.
    default: ansible_default_ipv4.interface

gateway
    network gateway
    default: ansible_default_ipv4.gateway

prefix
    default: 24

domain
    default: localdomain


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - common

License
-------

BSD

Author Information
------------------

James A. Kyle
james@jameskyle.org
https://github.com/jameskyle
