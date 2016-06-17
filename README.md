Role Name
=========

Adds upstart configuration for a unicorn process. Does not install unicorn as it assumes the application bears this responsibility.

Requirements
------------

No requirements.

Role Variables
--------------

ansible_upstart_unicorn_user: the owner of the unicorn process
ansible_upstart_unicorn_rack_env: either none, development or deployment
ansible_upstart_unicorn_app_path: the base application path

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: amaabca.ansible-upstart-unicorn }

License
-------

BSD

Author Information
------------------

https://github.com/amaabca/ansible-upstart-unicorn
