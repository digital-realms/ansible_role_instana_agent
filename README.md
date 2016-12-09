Role Name
=========
Master: [![Build Status](https://travis-ci.org/digital-realms/ansible_role_instana_agent.svg?branch=master)](https://travis-ci.org/digital-realms/ansible_role_instana_agent)

This role installs the Instana agent and configures it to a state that is running and pushing metrics to their SaaS environment.

The README is still a WIP and the module is an initial commit. it has been targetted towards CentOS 6 & 7 so far, however, we'll be expanding it's scope further along to cover Debian based machines.

Requirements
------------

This role requires Oracle JDK 8 to be installed. OpenJDK should work too, however is not mentioned in the documentation and therefore should be treated as not supported by the vendor.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
