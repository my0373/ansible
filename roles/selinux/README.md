Role Name
=========

Allow configuration of SELinux on RHEL7 systems

Requirements
------------

A RHEL 7 system to enable SELinux on.

Role Variables
--------------

Please see SELinux/defaults

Dependencies
------------

Ansible 2.5 minimum

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Configure SELinux
      hosts:  all
      remote_user: ansible
      roles:
        - { role: SELinux }

License
-------

MIT

Author Information
------------------

Matt York (my0373@gmail.com)