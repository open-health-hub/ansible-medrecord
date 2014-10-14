Role Name
========

Provision MedRecord

Requirements
------------

The desire to play with openEHR necessary...


Galaxy and Vagrant
------------
Created for ansible 1.7.2 for use with Vagrant 1.6.5 for MEDrecord.nl provisioning of Vagrant box on Ubuntu/Trusty64.

Install with Ansible Galaxy as follows:
- ansible-galaxy install robdyke.medrecord

Vagrant
- git clone https://github.com/openGPSoC/vagrant-medrecord.git
- cd vagrant-medrecord
- vagrant up


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
