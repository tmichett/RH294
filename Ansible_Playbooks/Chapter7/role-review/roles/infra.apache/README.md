infra.apache
=========

The infrastructure team has developed this role to install and configure httpd on a server.

Requirements
------------

None.

Role Variables
--------------

Copy the main.yml file in the defaults directory to the appropriate group_vars directory.
This file contains more information on the variables.

Dependencies
------------

None

Example Playbook
----------------

Below is an example of how to use the role

    - hosts: web_servers
      roles:
         - role: infra.apache


