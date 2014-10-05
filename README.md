Role Name
========

Provision MedRecord

Requirements
------------

The desire to play with openEHR necessary...

Role Variables
--------------

Defaults to pulling MedRecord from https://github.com/MEDvision/medrecord.git and installing to /opt

- medrecord_user: medrecord
- medrecord_base: /opt/medrecord
- medrecord_repo: https://github.com/MEDvision/medrecord.git

Dependencies
------------

- briancoca.oracle_java7
- robdyke.maven


Example Playbook
-------------------------

    - hosts: servers
      roles:
         - ansible-medrecord

License
-------

MIT

Author Information
------------------

@robdykedotcom for @opengpsoc
