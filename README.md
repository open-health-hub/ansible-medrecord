Role Name
========

Provision MedRecord

Requirements
------------

The desire to play with openEHR necessary...

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

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
