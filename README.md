JENKINS
=========

Ansible role to install and configure jenkins and to add a sample pipeline job which is  ready to build.

Requirements
------------

git

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

To build the job installation of sonarqube and nexus is required
available on my git hub page
ansible-role-sonar
ansible-role-nexus

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - jenkins

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
