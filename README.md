ans-role-linux-base
===================

A role to set up base packages on Ubuntu or Centos servers

Requirements
------------
None

Role Variables
--------------
locale - server locale eg en_GB.UTF-8
timezone - server localtime timezone eg Europe/London

Dependencies
------------
n/a

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-linux-base }

License
-------
MIT


Author Information
------------------
Brian Macauley
brian.macauley@gmail.com
