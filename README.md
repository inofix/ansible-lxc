LXC
===

Install the Linux Container support.

State
-----

Unstable.

Installation
------------

    # ansible-galaxy install inofix.ansible_lxc

Requirements
------------

* Ansible >2.0
* Python2/3 on target host
* Generic UNIX with FHS
* Sudo

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - inofix.ansible_lxc

License
-------

GPLv3

Author Information
------------------

* Michael Lustenberger at [inofix.ch](http://www.inofix.ch)

