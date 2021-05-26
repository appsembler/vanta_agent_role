Vanta Agent Role
=========

Ansible role to install Vanta agent.

Requirements
------------

You will need your vanta key and owner email. Get those by logging
into Vanta and then going to: https://app.vanta.com/downloads

Role Variables
--------------

* `vanta_key`, `vanta_owner_email` - get those from your Vanta account
* `vanta_version` - default "v1.8.5"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars:
         - vanta_key: your-vanta-key
         - vanta_owner_email: you@yourdomain.com
      roles:
         - vanta_agent_role

License
-------

MIT
