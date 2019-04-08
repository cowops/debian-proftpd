Debian-ProFTPD
===============

Highly configurable GPL-licensed FTP server software

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

proftpd:
  version: 1.3.5
  port:
    admin: 8083
    api: 8086

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-proftpd, proftpd.version: 1.3.6 }

Tasks
-----

  - Install [ProFTPD](http://www.proftpd.org/)

License
-------

BSD
