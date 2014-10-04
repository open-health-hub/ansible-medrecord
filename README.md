Role Name
========

Provision MedRecord

Requirements
------------

The desire to play with openEHR necessary...

Role Variables
--------------

Defaults to pulling MedRecord from https://github.com/MEDvision/medrecord.git and installing to /opt for user medrecord

Check in vars and defaults

Dependencies
------------

Use robdyke.java robdyke.maven MagneDavidsen.gradle get the deps installed

Needs Java, Maven, Gradle, Git

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: openGPSoC/ansible-medrecord, x: 42 }

License
-------

MIT

Author Information
------------------

@robdykedotcom for @opengpsoc
