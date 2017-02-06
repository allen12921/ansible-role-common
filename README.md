Role Name
=========

common role for fresh centos6,7 server configurationi:enable ntp,set timezone to UTC,install zabbix client,disable selinux and firewalld

------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

new.yml
---
- hosts: servers
  vars:
    - ZABBIX_SERVER: ZABBIXSERVER_IP
  roles:
    - { role: allen12921.common}

ansbile-playbook new.yml 

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
