Ansible Apt-cacher-NG Role for Debian
===========================

Features:
---------
* configures apt-cacher-ng
* adds debian security
* adds opensuse repositories

Supported Platforms:
--------------------
- Debian stretch

Changelog:
----------

Usage:
------
The role requires a filepath under `/var/cache/apt-cacher-ng`. This can be the root
filesystem or another directory.  

Notes: 
------
Currently the role assumes that uid 123 and gid 133 are the apt-cacher-ng user/group ids.
