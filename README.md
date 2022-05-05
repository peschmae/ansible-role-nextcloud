peschmae-nextcloud
=========

Installs nextcloud initially, and manages extensions & configuration. 

Does not support upgrading nextcloud! (Use the webui for it)

Requirements
------------

The role doesn't manage php or the webserver on the host.

It only installs nextcloud to a configured directory, creates & manages a configuration file for it, and creates the default cronjobs

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```
- hosts: nextcloud
  roles:
      - { role: peschmae.nextcloud, tags: ['nextcloud'] }
```

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
